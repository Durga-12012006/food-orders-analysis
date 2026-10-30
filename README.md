# Food Orders Analysis 🍽️

This repository contains an end-to-end Exploratory Data Analysis (EDA) and data cleaning pipeline for a food delivery dataset using Python.

## 🚀 Project Overview
The objective of this project is to analyze food delivery and order transactions to uncover insights regarding customer behavior, payment preferences, order channels, delivery times, and platform profitability.

## 📊 Key Tasks & Steps Performed
1. **Data Loading & Inspection:** Loaded 1,000 order records, inspected data types, column distributions, and summarized statistical metrics.
2. **Data Quality Assessment:** Checked for missing values, exact duplicates, and financial anomalies.
3. **Data Cleaning & Preprocessing:** 
   - Handled missing transaction fees and order values without artificial zero-imputation.
   - Filled missing categorical entries appropriately (`Unknown`, `Not Specified`).
   - Converted timestamps to proper datetime objects.
4. **Feature Engineering:**


   - Calculated delivery duration in minutes (`Delivery_Time_Minutes`).
   - Extracted order dates and hours (`Order_Hour`).
   - Computed Platform Net Revenue based on commissions, delivery fees, processing fees, and refunds.
5. **Business Insights & Answers:** Analyzed total order values, Average Order Value (AOV), top payment methods, and popular order channels.
6. **Data Visualization:** Plotted bar charts using Seaborn and Matplotlib to visualize orders by channel and payment methods.

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Environment:** Jupyter Notebook (`.ipynb`)

## 📈 Key Insights Summary
- **Total Order Value:** ₹1,013,415.00
- **Mean AOV:** ₹1,055.64
- **Top Payment Method:** Cash on Delivery
- **Top Order Channel:** Mobile App
- **Mean Delivery Time:** 73.58 minutes
