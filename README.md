# ICU Stay Duration Analysis Post Neuro-Surgical Procedures

## Project Overview
This project investigates factors associated with the duration of ICU stays post neuro-surgical procedures in ten tertiary hospitals in New York City. An observational study was conducted using random sampling to retrieve patient records for surgeries performed from February 14, 2016, to March 5, 2017. 

## Data Description
The dataset, “Research Analyst.xlsx,” contains patient records including demographic, clinical, and socioeconomic information, as well as post-operative outcomes.

## Steps and Methods

## Installation
Required packages:

library(readxl)


library(mice)


library(corrplot)


library(dplyr)

###  Data Loading
Data is loaded into R with the `read_excel` function and labeled as `test_thera`.

### Descriptive Analysis & Imputation
Descriptive statistics are performed on `duration of operation` and `systolic bp preoperative`, and missing values are imputed using MICE (Multiple Imputation by Chained Equations).

### Descriptive Statistics and Visualization
Descriptive statistics and visualizations are developed for five chosen variables to present the findings to stakeholders.

###  Risk Group Analysis
Analysis of variables is performed to compare characteristics between "low-risk" and "high-risk" groups defined by the duration of NICU stay.

###  Likelihood Analysis
A univariate analysis followed by a multivariate logistic regression analysis is conducted to assess the likelihood of being in the "low-risk" or "high-risk" group, based on factors that are statistically significant.

## Results
The multivariable model is the best fit among the models we've compared. This suggests that the combined effect of the predictors in the multivariate model provides a better understanding of the outcome variable than any single predictor on its own.





