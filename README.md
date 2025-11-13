Elevate Internship — Task 1
🧹 Data Cleaning & Preprocessing (Upgraded Submission)

Welcome to my official submission for Elevate Internship Task 1.
This project focuses on performing end-to-end data cleaning, preprocessing, diagnostics, and documentation on a customer dataset.

This repository contains:

Raw dataset (with missing values, duplicates & inconsistencies)

Fully cleaned & enhanced dataset

Before–after comparison summary

Visual data validation plots

A Jupyter notebook with all steps

Interview-style Q&A on data cleaning concepts

Complete output ZIP package

📁 Repository Structure
📦 elevate-task1-data-cleaning-badamsrividya
 ┣ 📄 mall_customers_raw.csv
 ┣ 📄 elevate_task1_FULL_PACKAGE.zip
 ┣ 📄 README.md  ← (this file)


Inside the ZIP file:

📦 elevate_task1_FULL_PACKAGE
 ┣ 📄 mall_customers_raw.csv
 ┣ 📄 mall_customers_clean_enhanced.csv
 ┣ 📄 before_after_summary.csv
 ┣ 📄 data_summary.txt
 ┣ 📄 diagnostics.json
 ┣ 📄 interview_answers.md
 ┣ 📄 task1_notebook.ipynb
 ┣ 📷 plot_age_hist.png
 ┣ 📷 plot_income_hist.png
 ┣ 📷 plot_spending_hist.png
 ┣ 📷 plot_gender_count.png
 ┗ 📷 plot_income_boxplot.png

🎯 Project Objective

The goal of this task is to:

Identify and fix common data quality issues, such as:

Missing values

Duplicate entries

Inconsistent formatting

Wrong data types

Inaccurate categories

Mixed date formats

Create a fully cleaned and analysis-ready dataset

Document all steps clearly

Prepare validation plots and summaries


🚀 Key Steps Performed
✔ 1. Missing Values Handled

Filled missing IDs using sequential fallback ID generation

Cleaned categorical missing values

Treated missing ages, incomes, dates etc.

✔ 2. Duplicates Removed

Identified duplicate CustomerID rows

Removed exact and semi-duplicate entries

✔ 3. Datatypes Fixed

Converted Age, Income, Spending Score → Numeric

Standardized JoinDate → Datetime

Uniform gender categories

✔ 4. Feature Engineering Added

Added tenure_years (based on JoinDate)

Added income_category (Low, Medium, High)

Binary gender encoding (Male=1, Female=0)

✔ 5. Data Quality Validation

Generated plots for:

Age distribution

Income distribution

Spending score

Gender count

Income boxplot

✔ 6. Before–After Summary

Included in: before_after_summary.csv

📊 Sample Visuals

(Charts available inside ZIP)

Age Histogram

Income Histogram

Spending Score Histogram

Gender Count Bar Graph

Income Boxplot

These visuals help verify outliers, skewness, and distribution shape.

📘 Notebook

The notebook (task1_notebook.ipynb) contains:

Full cleaning pipeline

Code explanations

Feature engineering steps

Validation sections
Final Output

📦 Full deliverables are available in:

elevate_task1_FULL_PACKAGE.zip

This ZIP is submission-ready for Elevate Internship Task 1.

👩‍💻 About Me

Badam Sri Vidya
4th year B.Tech CSE (Data Science)
Interested in Data Analytics, Machine Learning & Problem Solving.
