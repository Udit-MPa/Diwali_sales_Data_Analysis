# Diwali_sales_Data_Analysis
Exploratory data analysis of Diwali sales data using Python (Pandas, Matplotlib, Seaborn) to uncover customer buying patterns by demographics and product category.
# Diwali Sales Data Analysis

## Overview
An exploratory data analysis (EDA) project on retail sales data collected during the Diwali festive season, built using Python. The goal is to understand *who* buys the most and *what* they buy, so a business can make data-driven marketing and inventory decisions.

## Dataset
- ~11,000 sales transactions
- Fields include customer demographics (Gender, Age, Marital Status, Occupation, State) and order details (Product Category, Product ID, Orders, Amount)

## Tools & Libraries
- Python
- Pandas – data cleaning and aggregation
- Matplotlib & Seaborn – data visualization
- Jupyter Notebook

## Process
1. **Data Cleaning** – Removed irrelevant/blank columns, dropped null values, and corrected data types (e.g., converting Amount to integer).
2. **Exploratory Data Analysis** – Analyzed sales patterns across:
   - Gender
   - Age Group
   - State
   - Marital Status
   - Occupation
   - Product Category
3. **Visualization** – Used bar plots and count plots to compare purchasing behavior across each segment.

## Key Insights
- Married women aged 26–35 are the biggest spenders.
- Uttar Pradesh, Maharashtra, and Karnataka generate the highest order volume and sales.
- Customers working in IT, Healthcare, and Aviation purchase the most.
- Food, Clothing, and Electronics are the top-selling product categories.

## Conclusion
Married women aged 26–35 from UP, Maharashtra, and Karnataka working in IT, Healthcare, and Aviation are the most likely to purchase Food, Clothing, and Electronics — useful for targeted marketing campaigns during festive sales periods.

## How to Run
1. Clone the repo
2. Install dependencies: `pip install pandas numpy matplotlib seaborn`
3. Open `Diwali_Sales_Analysis.ipynb` in Jupyter Notebook and run all cells
