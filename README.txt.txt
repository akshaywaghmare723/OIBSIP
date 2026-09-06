# Cleaning Data - Titanic Dataset

## Project Overview
This project focuses on cleaning a deliberately messy Titanic dataset and preparing it for analysis.

## Objective
The objective is to identify and handle missing values, duplicate records, inconsistent formatting, incorrect data types and outliers.

## Tools Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Data Cleaning Performed
- Data quality report
- Missing value handling
- Duplicate removal
- Data standardization
- Outlier detection using IQR
- Data type correction
- Before and after data quality comparison
- Cleaned dataset export

## Missing Data Handling
- Age missing values were filled using the median.
- Cabin missing values were filled with "Unknown".
- Embarked missing values were filled using the mode.

## Duplicate Removal
Duplicate rows were checked and removed. No duplicate rows were found.

## Outlier Detection
Fare outliers were detected using the IQR method. 116 potential outliers were identified and retained because high fares can represent legitimate passenger fares.

## Output
The cleaned dataset was saved as:
cleaned_titanic.csv

## Conclusion
The Titanic dataset was cleaned and transformed into an analysis-ready dataset using Python, Pandas and NumPy.