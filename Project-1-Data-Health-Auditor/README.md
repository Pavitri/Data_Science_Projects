### 📌 Project 1: Automated Data Health Audit Tool
### 📖 Overview
Before diving into Data Cleaning, Exploratory Data Analysis (EDA), or Machine Learning, it is critical to evaluate the "health" of raw data. This project is a lightweight, automated Data Health Auditor built using Python and Pandas.

It inspects raw CSV and Excel datasets to detect common data quality issues like missing values, exact duplicate rows, repeated student IDs, extreme out-of-bounds anomalies (e.g., negative ages), and inconsistent categorical formatting.

### 📁 Included Files
1. data_health_checker.ipynb: The main Jupyter Notebook containing step-by-step modular Python code to audit the dataset.
2. Student_Data_With_Missing_Incorrect_Values.csv: The target dataset containing real-world data quality issues for testing and demonstration.

### 🔍 Audit Features & Checks
Schema & Structural Inspection: Summarizes total row count, column count, and identifies data types for every column.

Missing Data Detection: Identifies columns containing null/blank values, displaying exact missing counts and percentage ratios.

Duplicate Record Identification: Checks for fully duplicated rows as well as repeated unique primary keys (Student_ID).

Data Anomaly & Outlier Checks: Flags logical rule violations such as negative values or unrealistically high values in numerical columns (e.g., Age < 0 or Age > 100).

Inconsistent Category Detection: Checks string column values for inconsistent case/formatting entries (e.g., 'Male'/'Female' vs 'M'/'F').

Memory Footprint Analysis: Calculates the total memory allocation of the dataset in Kilobytes (KB).

### 🛠️ Requirements & Setup
To run this project locally on your machine:  pip install pandas numpy openpyxl notebook

Open Jupyter Notebook and execute "data_health_checker.ipynb" cell by cell.
