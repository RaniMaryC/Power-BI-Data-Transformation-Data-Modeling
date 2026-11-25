# Power BI - Data Transformation & Data Modeling

## Overview
This repository contains Assignment 1 of Power BI. It focuses on cleaning, transforming, and modeling data in Power Query and Power BI to prepare it for accurate reporting and dashboard creation.

## Tools Used
- Power BI Desktop
- Power Query Editor
  

## Files in this Repository
- `PowerBI-Assignment1.pbix` - Main Power BI file with data model and transformations
- `Power BI Assignment 1 - Raw Data Set.xlsx` - Raw dataset used for this assignment
- `Power BI Assignment 1 - Documentation.docx` - Step-by-step documentation with screenshots

## Work Done

### 1. Data Transformation (Power Query)
- Removed duplicates and null values
- Changed data types (Date, Text, Number)
- Split columns and renamed columns
- Replaced values and trimmed extra spaces

### 2. Calculated Columns
- Created `Month of Order Date` from Order Date
- Created `Sales` = Quantity * Unit Price
- Created `Profit` and other required columns using DAX

### 3. Group By
- Grouped data by Category and Month to get Total Sales, Total Quantity and Total Profit

### 4. Data Modeling
- Created relationships between tables:
- List of Orders (1) -> Order Details (Many) using Order ID
- Order Details (Many) -> Sales Target (Many) using Category / Month
- Sales Target (Many) -> Orders Data (Many) using Category

## Key Learning
Clean and well-structured data is the foundation for accurate dashboards. Data Modeling with proper relationships helps filters and visuals work correctly across all tables.

## Author
Rani Mary C
