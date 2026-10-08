# SWYNEX Final Data Analytics Project

## 1. Project Overview

This project combines the complete data analytics workflow performed during the SWYNEX Technologies internship.

The project covers:
- Data Cleaning and Preparation
- Exploratory Data Analysis (EDA)
- Interactive Power BI Dashboard
- Key Business Insights

## 2. Problem Statement

The objective of this project is to analyze global e-commerce sales data and identify important sales patterns, category performance, country-wise performance, and monthly sales trends.

The analysis helps understand overall sales performance and identify the categories and countries contributing most to sales.

## 3. Dataset Information

The dataset contains 1,200 e-commerce order records.

### Dataset Columns
- Order_ID
- Country
- Category
- Unit_Price
- Quantity
- Order_Date
- Total_Amount

## 4. Data Cleaning and Preparation

The dataset was checked using SQL in MySQL Workbench.

### Missing Values
All columns were checked for NULL values.

**Result:** No missing values found.

### Duplicate Records
Duplicate Order_ID values were checked using GROUP BY and HAVING.

**Result:** No duplicate Order_IDs found.

### Data Types
Column data types were checked using DESCRIBE.

Order_Date was stored as TEXT and the original format was retained.

### Consistency Check
Country and Category values were checked using DISTINCT.

**Result:** Values were consistent.

### Invalid Numeric Values
Unit_Price, Quantity and Total_Amount were checked for zero or negative values.

**Result:** No invalid numeric values found.

### Total Amount Validation

The following calculation was validated:

Unit_Price × Quantity = Total_Amount

**Result:** No inconsistencies found.

### Date Validation

Order_Date was validated using STR_TO_DATE with the MM/DD/YYYY format.

## 5. Exploratory Data Analysis

The cleaned dataset was analyzed to understand sales performance.

### Overall Performance

- Total Sales: ₹1,512,252.98
- Total Quantity: 6,008
- Total Orders: 1,200

### Category-wise Sales

Home Decor had the highest total sales.

Top categories by sales:

1. Home Decor
2. Grocery
3. Electronics
4. Fashion
5. Sports

### Country-wise Sales

Country-wise sales were analyzed to identify the strongest-performing markets.

### Monthly Sales Trend

Monthly sales were analyzed using the Order_Date field.

July recorded the highest monthly sales in the analyzed period.

## 6. Interactive Power BI Dashboard

An interactive Power BI dashboard was created to present the analysis visually.

### Dashboard Components

- Total Sales KPI
- Total Orders KPI
- Total Quantity KPI
- Average Order Value KPI
- Category filter
- Country filter
- Sales by Category
- Sales by Country
- Monthly Sales Trend
- Top 5 Categories by Sales

## 7. Key Business Insights

- Home Decor was the highest-selling category.
- Grocery and Electronics were also strong-performing categories.
- USA recorded the highest country-wise sales.
- July was the strongest month in the monthly sales trend.
- The Top 5 category view highlights the strongest sales contributors.
- Category and Country filters allow interactive analysis.

## 8. Tools Used

- MySQL Workbench
- SQL
- Power BI
- GitHub

## 9. Project Outcome

The complete workflow transformed the raw e-commerce sales dataset into a cleaned, analyzed and visualized analytics solution.

The final project includes data cleaning, exploratory analysis, an interactive dashboard and business insights.
