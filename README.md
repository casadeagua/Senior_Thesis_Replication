# Echoes Without Resonance: Applied ML in Political Economy
**Author:** Austin Waterhouse 
**Status:** Senior Thesis | Awarded Highest Honors (UCSD)  
**Primary Toolstack:** R (Tidyverse, Quanteda, STM), Machine Learning (NLP)

---

### [Click Here to Read the Full Thesis Paper](Thesis_Final_Post.pdf)

## Project Overview
This repository contains the end-to-end research pipeline for my senior honors thesis. The project investigates the relationship between campaign finance and legislative discourse by applying **Machine Learning** and **Structural Topic Modeling (STM)** to over a century of congressional records.

## Key Research & Data Functions
To execute this analysis, I performed the following professional research tasks:

* **Data Construction & Cleaning:** Aggregated and merged three large-scale disparate datasets (Textual, Financial, and Public Opinion) into a unified panel for analysis.
* **Text Preprocessing (NLP):** Developed a custom pipeline in R to clean, tokenize, and filter phrase counts from the 43rd–114th Congresses (Stanford Hein-Daily dataset).
* **Statistical Analysis:** Formulated a Dependent Variable using Topic Modeling to measure legislative resonance; conducted regression analysis to test political economy hypotheses.
* **Data Visualization:** Designed publication-quality figures and tables using `ggplot2` to communicate complex statistical findings.

## Usage Tutorial
Download all files and data sources. Warning, the data sources are large and may take several hours to download. 
Then, set the directories to where you downloaded the data.
Next, run the "AllinOnedoc.R" File.
This will take a couple hours (depending on hardware)
This will create the topic model, run analysis, and create the graphs.

Alternatively, you can run each file seperately, and save your progress along the way. Do this if you are having problems with computing the entire code at once.

## Data Sources
This project integrates the following primary sources:

1.  **Congressional Record (Stanford):** Parsed Speeches and Phrase Counts (43rd–114th Congress). [Link](https://data.stanford.edu/congress_text)
2.  **Campaign Finance Data (OpenSecrets):** 1994–2014 Cycle Tables. [Link](https://www.opensecrets.org/bulk-data/downloads)
3.  **Public Opinion Data (Policy Agendas Project):** Gallup "Most Important Problem" dataset. [Link](https://www.comparativeagendas.net/datasets_codebooks)

## Reproducibility Note
The code is structured to be modular and reproducible. While file paths are currently configured for a local environment, I am in the process of updating scripts to use relative paths for easier cross-platform execution.

## Contact
**Name:** Austin Waterhouse
**Email:** 2austin99@gmail.com 

*I am happy to discuss the methodology, data construction challenges, or specific findings in detail.*
