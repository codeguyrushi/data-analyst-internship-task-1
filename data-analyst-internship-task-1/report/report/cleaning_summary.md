# Data Cleaning Summary

## Dataset
Netflix Movies and TV Shows

## Objective
The objective was to clean and preprocess the raw dataset by handling
missing values, duplicate records, inconsistent text formatting,
column names, dates, and data types.

## Cleaning Steps

### 1. Missing Values
Missing values in descriptive text columns were replaced with "Unknown"
where appropriate.

### 2. Duplicate Records
Duplicate rows were identified and removed using Pandas drop_duplicates().

### 3. Column Names
Column names were standardized by converting them to lowercase and
replacing spaces with underscores.

### 4. Text Standardization
Leading/trailing spaces were removed and categorical text values were
standardized.

### 5. Date Formatting
Date columns were converted to Pandas datetime format.

### 6. Data Types
Columns were checked and converted to appropriate data types.

## Result
The final dataset was checked for missing values, duplicates,
inconsistent formats, and incorrect data types and was saved as
cleaned_dataset.csv.