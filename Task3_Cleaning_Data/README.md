# OIBSIP – Data Analytics Internship

## Task 3: Cleaning Data

### 📌 Objective

The objective of this task is to demonstrate professional-level data cleaning
skills by transforming a deliberately messy dataset into a clean,
analysis-ready dataset using Python, Pandas and NumPy.

### 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Jupyter Notebook

### 🔍 Data Cleaning Process

The following data cleaning techniques were implemented:

1. Loaded the raw dataset.
2. Generated a data quality report.
3. Checked missing values for each column.
4. Identified and removed duplicate records.
5. Standardized inconsistent categorical values.
6. Converted columns to appropriate data types.
7. Detected numerical outliers using the IQR method.
8. Evaluated whether outliers should be retained, capped or removed.
9. Handled missing values using appropriate strategies.
10. Compared the dataset before and after cleaning.
11. Exported the final cleaned dataset as a CSV file.

### 📊 Data Quality Report

The notebook includes:

- Null values per column
- Duplicate row count
- Data type validation
- Numerical range checks
- Outlier detection

### 🧹 Missing Data Handling

Missing values were handled according to the nature of each column.
Numerical variables were evaluated for mean/median imputation,
categorical variables for mode imputation, and rows were removed only
where deletion was appropriate.

Each decision and its justification are documented in the notebook.

### 🔄 Standardization

Inconsistent categorical values were normalized to a common format.

Examples:

- Male / male / M → Male
- Female / female / F → Female

Date columns were converted to the appropriate datetime format.

### 📈 Outlier Detection

The IQR (Interquartile Range) method was used to identify potential
outliers in numerical columns.

Outliers were reviewed individually and were retained, capped or removed
depending on whether they represented valid observations or data errors.

### 📋 Before vs After

The notebook provides a comparison of:

| Metric | Before Cleaning | After Cleaning |
|---|---:|---:|
| Row Count | Documented in notebook | Documented in notebook |
| Null Values | Documented in notebook | Documented in notebook |
| Duplicate Rows | Documented in notebook | Documented in notebook |
| Data Type Issues | Identified | Corrected |

### 📁 Project Files

- KhushiChaudhary_Task3.ipynb – Complete Jupyter Notebook
- messy_dataset.csv – Original dataset
- KhushiChaudhary_Task3_Cleaned.csv – Cleaned dataset
- screenshots/ – Project demonstration screenshots

### ✅ Outcome

The final dataset is cleaned, standardized and ready for further
analysis or machine learning applications.

### 👩‍💻 Author

Khushi Chaudhary

Data Analytics Intern – Oasis Infobyte
