# Sales-Data-Analysis-using-Pandas
The Sales Data Analysis project involves processing an Excel-based retail dataset containing invoice details, pricing, discounts, quantities, and profit information.  The project begins with data cleaning, where currency symbols, percentage values, and inconsistent column names are standardized. 
# 📊 Sales Data Analysis Project
👨‍💻 Developed by

# Savar Bajiya

📌 Introduction

This project focuses on analyzing a retail sales dataset using Python and Pandas to extract meaningful business insights. The analysis covers data cleaning, preprocessing, KPI generation, exploratory data analysis (EDA), and visualization.

The primary goal of this project is to transform raw sales data into actionable insights that help understand product performance, sales trends, profitability, and operational efficiency.

This project reflects a real-world data analyst workflow and demonstrates practical skills required in the analytics industry.

# 🎯 Project Objectives

Clean and preprocess raw sales data

Handle missing and inconsistent values

Convert textual and currency fields into usable numeric data

Create business KPIs such as Revenue, Cost, and Profit

Perform exploratory data analysis

Generate insights for business decision-making

Visualize trends and performance patterns

# 📁 Dataset Overview

The dataset contains transactional retail sales data with invoice-level details.

Key Columns:

Date

Invoice Number

Item Code

Sales Person

Manager On Duty

Ticket Price

Discount Given

Sales Price Per Unit

Cost per Unit

Quantity

Postal Code

Total Sales per Invoice

Discount Amount

Total Profit

This dataset represents real-world business operations and is suitable for practicing data cleaning, analysis, and reporting.

# 🛠 Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib

Jupyter Notebook / Google Colab

# 🧹 Data Cleaning Process

The raw dataset required preprocessing before analysis.

Steps performed:

Removed currency symbols ($) from price columns

Removed percentage (%) symbols from discount column

Converted text-based numeric values into numeric data types

Standardized column names

Converted date column into datetime format

Handled missing and invalid values

This ensured accurate and reliable analysis.

# 📊 KPI & Feature Engineering

New business metrics were created to support analysis:

Revenue = Sales Price × Quantity

Total Cost = Cost per Unit × Quantity

Profit = Revenue − Cost

Profit Margin %

Monthly sales grouping

These KPIs help measure performance and profitability.

# 🔎 Exploratory Data Analysis (EDA)

The following analyses were performed:

Product Analysis

Top-performing products

Low-performing products

Profit contribution by item

Sales Performance

Salesperson ranking

Manager performance comparison

Quantity vs profit relationship

Discount Analysis

Impact of discounts on profit

Discount vs revenue trends

Regional Analysis

Revenue by postal code

High-performing locations

Time-Based Analysis

Daily sales trends

Monthly revenue trends

Peak sales days

# 📈 Visualizations Created

Sales by salesperson (bar chart)

Profit trend over time (line chart)

Monthly revenue trend

Quantity vs profit scatter plot

Visualizations help communicate insights effectively.


# 🚀 How to Run the Project
Step 1: Install dependencies
pip install pandas matplotlib openpyxl

Step 2: Run the analysis
python sales_analysis.py


Or open the notebook in Jupyter/Colab and run all cells.
