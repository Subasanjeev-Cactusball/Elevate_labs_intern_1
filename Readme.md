# Data Analytics Internship Tasks

## Overview

This repository contains my Data Analytics internship tasks, completed using Python, Pandas, Jupyter Notebook, and Microsoft Power BI.

The projects demonstrate practical experience in data cleaning, preprocessing, visualization, dashboard development, and data storytelling.

---

# Task 1 — Data Cleaning and Preprocessing

## Objective

The objective of this task was to clean and preprocess a raw customer dataset containing common data-quality issues such as missing values, duplicate records, inconsistent text formatting, and data-type issues.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Dataset

The project uses a customer dataset containing information such as:

- Customer ID
- Customer Name
- Customer Age
- Gender
- Customer Segment
- Customer City
- Customer State
- Customer Country
- Region
- Postal Code
- Customer Acquisition Cost

## Data Cleaning Steps

The following steps were performed:

1. Loaded the raw dataset using Pandas.
2. Inspected the dataset structure and columns.
3. Checked for missing values.
4. Handled missing values.
5. Identified and removed duplicate records.
6. Checked and corrected data types.
7. Removed unnecessary leading and trailing spaces.
8. Standardized categorical/text values.
9. Validated customer age values.
10. Checked customer acquisition cost values.
11. Verified customer ID uniqueness.
12. Performed final data-quality validation.
13. Exported the cleaned dataset as a CSV file.

## Final Dataset

The cleaned dataset contains:

- **25,000 records**
- **11 columns**
- **0 missing values**
- **0 duplicate records**

## Task 1 Files

| File | Description |
|---|---|
| `Task_1_Data_Cleaning_Preprocessing.ipynb` | Complete Python/Jupyter Notebook |
| `cleaned_customer_dataset.csv` | Final cleaned dataset |

---

# Task 2 — Data Visualization and Storytelling

## Objective

The objective of this task was to create meaningful visualizations that communicate customer-related information clearly and provide useful business insights.

## Tool Used

- Microsoft Power BI

## Dashboard

A Power BI dashboard was created using the cleaned dataset from Task 1.

The dashboard contains the following visualizations:

### 1. Total Customers
A KPI card displaying the total number of customers.

### 2. Average Customer Acquisition Cost
A KPI card showing the average cost of acquiring a customer.

### 3. Customer Distribution by Gender
A donut chart showing the distribution of customers by gender.

### 4. Customer Distribution by Segment
A bar/column chart comparing the number of customers across different customer segments.

### 5. Customer Age Distribution
A column chart showing the distribution of customers across different age groups.

### 6. Customers by Region
A bar chart showing customer distribution across regions.

### 7. Customers by Country
A bar chart showing customer distribution across countries.

### 8. Average Acquisition Cost by Customer Segment
A column chart comparing the average acquisition cost across customer segments.

## Dashboard Design Principles

The dashboard was designed with the following principles:

- Use the appropriate chart for each type of data.
- Avoid unnecessary visual clutter.
- Maintain a consistent visual design.
- Use clear and descriptive chart titles.
- Display important KPIs prominently.
- Focus on business insights rather than only displaying charts.
- Present the information in a simple and understandable format.

## Task 2 Files

| File | Description |
|---|---|
| `Task_2_Data_Visualization_and_Storytelling.pdf` | Exported visual report |
| `Dashboard_Screenshot.png` | Power BI dashboard screenshot |
| `Customer_Data_Visualization.pbix` | Power BI project file |

---

# Project Workflow

The overall workflow followed in these tasks was:

```text
Raw Customer Dataset
        ↓
Data Inspection
        ↓
Data Cleaning
        ↓
Data Preprocessing
        ↓
Data Validation
        ↓
Cleaned Dataset
        ↓
Power BI Visualization
        ↓
Dashboard
        ↓
Data Storytelling & Business Insights
