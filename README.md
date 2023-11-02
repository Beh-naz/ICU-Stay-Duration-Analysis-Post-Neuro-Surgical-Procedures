# ICU Stay Duration Analysis Post Neuro-Surgical Procedures

## Project Overview
This project investigates factors associated with the duration of ICU stays post neuro-surgical procedures in ten tertiary hospitals in New York City. An observational study was conducted using random sampling to retrieve patient records for surgeries performed from February 14, 2016, to March 5, 2017. A mixed methods design was employed, combining records review with patient interviews about indirect costs and quality of life using SF36 and EQ-5D-5L.

## Data Description
The dataset, “Research Analyst_16SEPT2021.xlsx,” contains patient records including demographic, clinical, and socioeconomic information, as well as post-operative outcomes.

## Tasks and Methods

### Task 1: Data Loading
Data is loaded into R with the `read_excel` function and labeled as `test_thera`.

### Task 2: Variable Names
The variable names in the dataset are displayed.

### Task 3: Data Dimensions
The dimensions of the dataset are obtained, showing the number of rows and columns.

### Task 4: Viewing Data
Display the last 6 entries in the `age` column.

### Task 5: Renaming Columns
Column names for gender and systolic blood pressure preoperative are updated to `sex` and `blood pressure`, respectively.

### Task 6: Recoding Variables
The `income bracket` variable is recoded to reflect income ranges instead of numerical codes.

### Task 7: Income Bracket Display
The first 6 rows of the recoded `income bracket` are displayed.

### Task 8: Descriptive Analysis & Imputation
Descriptive statistics are performed on `duration of operation` and `systolic bp preoperative`, and missing values are imputed using MICE (Multiple Imputation by Chained Equations).

### Task 9: Descriptive Statistics and Visualization
Descriptive statistics and visualizations are developed for five chosen variables to present the findings to stakeholders.

### Task 10: Risk Group Analysis
Analysis of variables is performed to compare characteristics between "low-risk" and "high-risk" groups defined by the duration of NICU stay.

### Task 11: Likelihood Analysis
A univariate analysis followed by a multivariate analysis is conducted to assess the likelihood of being in the "low-risk" or "high-risk" group, based on factors that are statistically significant.

## Installation
Required packages:

library(readxl)


library(mice)


library(corrplot)


library(dplyr)

## Steps:
Loading data

## Results
A summary of key findings and insights derived from the analysis, possibly including tables or figures generated.





