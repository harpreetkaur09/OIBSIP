# Retail Sales Data Analysis – Exploratory Data Analysis

## Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales
dataset using Python. The analysis focuses on understanding sales trends,
customer demographics, product categories, and relationships between
numerical variables.

## Dataset

The dataset contains 1,000 retail transaction records and 9 columns:

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

## Data Preparation

The dataset was inspected for missing values, data types, and basic
data quality. No missing values were found. The Date column was converted
from string format to datetime format for time-based analysis.

## Analysis Performed

The following analysis was performed:

- Dataset structure and data quality check
- Descriptive statistics
- Monthly sales trend
- Quarterly sales trend
- Customer age-group distribution
- Gender distribution
- Top 10 transactions by quantity
- Revenue by product category
- Correlation matrix and heatmap
- Category-wise and gender-wise sales analysis

## Business Recommendations

1. Focus marketing efforts on customer age groups with higher transaction
   activity.

2. Give greater attention to product categories generating higher revenue.

3. Use category-wise and gender-wise sales patterns to support targeted
   marketing campaigns.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
Task1_Retail_EDA/
│
├── retail_sales_dataset.csv
├── retail_sales_eda.ipynb
└── README.md