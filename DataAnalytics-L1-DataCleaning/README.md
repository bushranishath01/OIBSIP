# Data Cleaning – Customer Sales Data Cleaning and Preprocessing

## Project Overview

This project focuses on cleaning and preprocessing a messy customer sales dataset using Python. The dataset initially contained 10,200 records and 12 columns, with missing values, duplicate records, inconsistent formatting, incorrect data types and unusual values.

## Objectives

- Identify missing values and duplicate records.
- Handle missing data using appropriate strategies.
- Standardise inconsistent categorical values.
- Correct data types and invalid entries.
- Detect and handle outliers using the IQR method.
- Compare data quality before and after cleaning.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Cleaning Process

1. Loaded and inspected the original dataset.
2. Assessed missing values, duplicates and data inconsistencies.
3. Standardised categorical columns such as Gender, City and Country.
4. Corrected data types and handled invalid values.
5. Applied missing-value treatment.
6. Detected and capped extreme purchase amounts using the IQR method.
7. Removed duplicate records.
8. Generated before-and-after comparisons and visualisations.

## Results

| Metric | Before Cleaning | After Cleaning |
|---|---:|---:|
| Records | 10,200 | 10,003 |
| Duplicate rows | 15 | 0 |
| Missing values | 7,804 | 2,917 |

## Conclusion

The cleaning process improved the consistency and quality of the customer sales dataset. Duplicate records were removed, inconsistent values were standardised, and missing and invalid values were handled using appropriate techniques. The final cleaned dataset was saved as a CSV file for further analysis.

## Project Files

- `OIBSIP_L1_Task3_Data_Cleaning.ipynb` – Jupyter Notebook containing the data cleaning process, analysis and visualisations.
- `cleaned_customer_sales.csv` – Final cleaned dataset exported after preprocessing.
- `README.md` – Project documentation.
