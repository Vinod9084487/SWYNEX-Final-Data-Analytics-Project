# SWYNEX Final Data Analytics Project

## Final Data Analytics Project

This project is the final analytics case study completed as part of my internship with SWYNEX Technologies.

The project combines data cleaning, exploratory data analysis and interactive dashboard development using the Indian School Education Statistics dataset.

## 1. Problem Statement

The objective of this project is to analyze school dropout statistics across different States/UTs and years, identify important trends and patterns, and present the findings through an interactive Power BI dashboard.

## 2. Dataset Information

The dataset used is the Indian School Education Statistics dataset.

It contains dropout statistics for different education levels across Indian States/UTs and years.

Dataset used:
- `dropout-ratio-2012-2015.csv`

The cleaned dataset contains 110 rows and 14 columns.

## 3. Data Cleaning

Python, Pandas and NumPy were used for data cleaning.

The following steps were performed:

- Checked the dataset structure and column names.
- Checked missing values.
- Checked duplicate records.
- Replaced `NR` values with missing values.
- Converted numerical columns to numeric data types.
- Checked the cleaned dataset.
- Saved the cleaned dataset as `cleaned_dropout_ratio.csv`.

## 4. Exploratory Data Analysis

Exploratory Data Analysis was performed using Python, Pandas, NumPy and Matplotlib.

The analysis included:

- Dataset structure analysis
- Missing value analysis
- Duplicate record analysis
- Descriptive statistics
- Average dropout rate by education level
- Yearly dropout trends
- Identification of unusually high values
- Data visualization

## 5. Key Insights

1. Secondary education has the highest average dropout rate among the four education levels analyzed.

2. Primary dropout rate decreased from 2012-13 to 2014-15.

3. Secondary dropout rate shows a slight increase over the analyzed years.

4. Some records contain unusually high dropout values, such as a Secondary dropout value of 49.86 for Odisha in 2012-13.

5. Higher Secondary has the highest number of missing values among the four total dropout columns.

## 6. Interactive Dashboard

A Power BI dashboard was created using the cleaned dataset.

The dashboard includes:

- Total States/UTs KPI
- Average Secondary Dropout KPI
- Average Upper Primary Dropout KPI
- Average Dropout Rate by Education Level
- Yearly Secondary Dropout Trend
- Average Secondary Dropout by State/UT
- Year filter
- State/UT filter

## 7. Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Power BI
- Google Colab
- GitHub

## 8. Project Files

- `cleaned_dropout_ratio.csv` – Cleaned dataset
- `Task2_EDA.ipynb` – Exploratory Data Analysis notebook
- `SWYNEX_Task3_Interactive_Dashboard.pbix` – Power BI dashboard
- `README.md` – Project documentation

## 9. Conclusion

This project demonstrates the complete data analytics process, from data cleaning and exploratory analysis to interactive dashboard development.

The analysis helped identify dropout patterns, yearly trends, differences between education levels and variations across States/UTs.

The Power BI dashboard provides an interactive way to explore these findings.
