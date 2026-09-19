# Task 1: Titanic Data Cleaning

## Overview
This repository contains the solution for Task 1 of the Synent Technologies Data Science Internship. The objective of this project is to clean and preprocess the Titanic dataset to prepare it for analysis.

## Key Steps Performed
1. **Data Loading:** Loaded the dataset directly using Pandas from the source repository.
2. **Missing Value Imputation:**
   - Imputed missing values in `Age` using median.
   - Imputed missing values in `Embarked` using mode.
   - Dropped the `Cabin` column due to a high percentage of missing values.
3. **Data Quality Checks:** Removed duplicate rows if any.
4. **Data Type Conversion:** Converted categorical features (`Sex`, `Embarked`) to category data types for optimal memory usage.
5. **Standardization:** Renamed columns to standard lowercase snake_case format.
6. **Output:** Exported the cleaned dataset as `cleaned_titanic_data.csv`.

## Technologies Used
- Python
- Pandas
- Google Colab / Jupyter Notebook
