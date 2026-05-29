# CODVEDA ASSIGNMENTS
# Codveda Data Analytics Internship

This repository contains my Data Analytics internship tasks completed for Codveda Technologies.

# Repository Structure

```text
codveda-data-analytics-internship/
│
├── README.md
│
└── Level-1/
    │
    ├── README.md
    ├── Level_1_House_Data_Cleaning_and_EDA.ipynb
    ├── level_1_house_data_cleaning_and_eda.py
    │
    ├── Task-1-Data-Cleaning-and-Preprocessing/
    │   ├── README.md
    │   └── cleaned_house_prediction_data.csv
    │
    └── Task-2-Exploratory-Data-Analysis/
        ├── README.md
        └── level_1_task_1_and_2_outputs.zip
```

# Level 1 - Basic

# Task 1: Data Cleaning and Preprocessing

# Dataset Used

House Prediction Dataset

# Objective

The objective of this task was to clean and preprocess a raw dataset using Python and pandas.

# Work Completed

* Loaded the dataset using pandas
* Assigned proper column names to the dataset
* Checked dataset structure using `df.info()`
* Checked for missing values using `df.isnull().sum()`
* Checked for duplicate rows using `df.duplicated().sum()`
* Removed duplicate rows
* Confirmed that all columns were numerical
* Exported the cleaned dataset as `cleaned_house_prediction_data.csv`

# Findings

The dataset contained 506 rows and 14 columns. No missing values were found. No duplicate rows were found. Since all columns were numerical, no categorical standardization or date formatting was required.



# Task 2: Exploratory Data Analysis

# Objective

The objective of this task was to perform exploratory data analysis on the cleaned House Prediction Dataset.

# Work Completed

* Calculated summary statistics including mean, median, mode, and standard deviation
* Created histograms to visualize numerical feature distributions
* Created boxplots to identify possible outliers
* Created scatter plots to analyze relationships between variables
* Created a correlation heatmap to identify relationships between numerical features
* Analyzed the correlation between house value and other features

# Key Findings

* RM has a positive relationship with MEDV, meaning house values tend to increase as the average number of rooms increases.
* LSTAT has a negative relationship with MEDV, meaning house values tend to decrease as LSTAT increases.
* Some variables such as CRIM and MEDV showed possible outliers.

# Tools Used

* Python
* pandas
* matplotlib
* seaborn
* Google Colab
* GitHub
