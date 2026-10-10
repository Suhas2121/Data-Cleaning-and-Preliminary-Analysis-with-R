# Data-Cleaning-and-Preliminary-Analysis-with-R

## Project Overview

This project focuses on cleaning and preparing the Titanic passenger dataset using R. The workflow includes data validation, missing-value treatment, outlier detection, feature engineering, descriptive statistics, and preliminary survival analysis.

The final cleaned dataset contains 891 valid passenger records with no remaining missing values.

## R Script

Main script:

`week1_data_cleaning.R`

The script performs:

- Dataset import and inspection
- Duplicate checking
- Missing-value analysis
- Missing-value imputation
- Outlier detection using the IQR method
- Feature engineering
- Variable encoding
- Data scaling
- Descriptive statistics
- Survival analysis
- Export of cleaned data and plots

## Dataset Source

Titanic passenger dataset.

The dataset contains passenger information including:

- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

## Usage

Place the Titanic CSV file in the project folder and run:

source("week1_data_cleaning.R")

The script generates the cleaned dataset, summary tables, and plots.

## Required R Packages

This project primarily uses Base R.

No additional packages are required for the main cleaning workflow.

## Important Output Charts

- Missing-value percentages
- Age and Fare outlier distributions
- Age distribution
- Survival by sex
- Survival by passenger class
- Survival by embarkation port
- Correlation heatmap

## Expected Results

The cleaned dataset should contain 891 valid passenger records with no remaining missing values.

Major findings include:

- Female survival rate: approximately 74.2%
- Male survival rate: approximately 18.75%
- First-class survival rate: approximately 62.96%
- Third-class survival rate: approximately 24.24%

The results show strong differences in survival based on sex and passenger class.

## Author

Suhas D
