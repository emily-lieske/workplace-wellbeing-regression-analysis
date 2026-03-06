# Workplace Burnout and Discrimination: Exploring the Relationship with Poor Mental Health

**Course:** Statistics for Data Science (W203) — UC Berkeley MIDS, Spring 2025  
**Team:** Carmen Liang, Emily Lieske, Margaret Lubega  

## Overview

This project investigates whether workplace burnout and experiences of discrimination are 
significant predictors of poor mental health. Using data from the 2018 General Social Survey 
(GSS), we built and evaluated a series of linear regression models to explore this relationship 
while controlling for relevant covariates.

Our analysis is motivated by growing concern around workplace wellbeing — particularly as 
burnout and workplace discrimination have become increasingly prevalent topics in public 
health and organizational research. This project aims to provide an empirically grounded 
look at how these factors relate to self-reported mental health outcomes.

## Key Questions

- Does workplace burnout predict poor mental health outcomes?
- Does experiencing workplace discrimination compound this effect?
- How do these relationships hold up after controlling for demographic and socioeconomic factors?

## Methods

- Exploratory Data Analysis (EDA) with visualizations
- Data cleaning and feature engineering from raw GSS data
- Ordinary Least Squares (OLS) linear regression modeling
- Model evaluation and assumption checking (heteroskedasticity-robust standard errors via `sandwich` and `lmtest`)

## Tech Stack

- **Language:** R
- **Key Packages:** `tidyverse`, `ggplot2`, `sandwich`, `lmtest`, `renv`, `here`
- **Data:** 2018 General Social Survey (GSS)


### Folder Structure and Purpose
├── LICENSE  
├── README.md          <- This file: describes the purpose and structure of the project.  
├── data  
│   ├── external       <- Raw data from the 2018 GSS (*Note: This is the **only file required** to run the Rmd file.*).  
│   ├── interim        <- Cleaned and filtered datasets created during data wrangling (*Note: **Not required** to run the Rmd file.*).  
│   └── processed      <- Final modeling-ready datasets (*Note: **Not required** to run the Rmd file.*).  
├── notebooks          <- The full R Markdown notebook with all analysis code, from data wrangling and cleaning to modeling and results.  
├── references         <- GSS codebook and variables description     
└── reports            <- Final report PDF and presentation slides used for class submission.  

### Disclaimer
This repository is for academic purposes only. While the dataset and methods are real, the project is exploratory in nature and should not be interpreted as definitive scientific research or policy guidance.
