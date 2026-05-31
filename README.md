# Data-analyst-Intern-Task-1

Tools Used
Python
Pandas
Microsoft Excel
Jupyter Notebook
Dataset

Dataset used: [Your Dataset Name]
Source: Kaggle

Data Cleaning Steps Performed
1. Missing Value Handling

Identified missing values using:

df.isnull().sum()
Handled missing values by:
Removing rows with excessive null values.
Filling missing values where appropriate.
2. Duplicate Record Removal

Checked for duplicate rows:

df.duplicated().sum()

Removed duplicates:

df.drop_duplicates(inplace=True)
3. Standardized Text Values
Standardized categorical columns such as Gender and Country.
Converted text to lowercase and mapped values to a consistent format.
4. Date Format Standardization
Converted date columns into a consistent format.
(in last data set i struggle for simple trick) 

In addition to Pandas, Excel was used to:

Identify duplicate values.
Remove duplicate records.
Standardize text entries.
Verify cleaned data manually.
Apply filters and conditional formatting for validation.
