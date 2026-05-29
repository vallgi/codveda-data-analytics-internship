# Codveda Data Analytics Internship

This repository contains my Data Analytics internship tasks completed for Codveda Technologies.

## Level 1 - Task 1: Data Cleaning and Preprocessing

### Dataset Used
House Prediction Dataset

### Objective
The objective of this task was to clean and preprocess a raw dataset using Python and pandas.

### Work Completed
- Loaded the dataset using pandas
- Assigned proper column names to the dataset
- Checked dataset structure using `df.info()`
- Checked for missing values using `df.isnull().sum()`
- Checked for duplicate rows using `df.duplicated().sum()`
- Removed duplicate rows
- Confirmed that all columns were numerical
- Exported the cleaned dataset as `cleaned_house_prediction_data.csv`

### Findings
The dataset contained 506 rows and 14 columns. No missing values were found. No duplicate rows were found. Since all columns were numerical, no categorical standardization or date formatting was required.

### Tools Used
- Python
- pandas
- Google Colab
