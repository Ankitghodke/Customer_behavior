# 📊 Customer Behavior Dashboard Project

 📌 Overview
This project analyzes customer shopping behavior data using Python for data cleaning and feature engineering, SQL (Neon PostgreSQL) for deep analysis, and Power BI for dashboard visualization.

The goal of the project is to generate meaningful business insights from raw customer purchase data.


 🔄 Project Workflow

 1️⃣ Data Import (Google Colab)
- Imported the CSV file into Google Colab.
- Performed initial inspection of the dataset.

 2️⃣ Python Work (Data Cleaning & Feature Engineering)
Using Pandas in Google Colab:
- Handled missing values
- Created calculated columns
- Structured the dataset for analysis

Python was mainly used for:
- Data preprocessing
- Feature engineering
- Preparing clean data for SQL analysis


 3️⃣ SQL Work (Neon PostgreSQL - Serverless)

Connected Google Colab to Neon PostgreSQL database.

SQL was used for:
- Creating tables
- Importing cleaned data into the database
- Writing analytical queries
- Using:
  - GROUP BY
  - SUM()
  - COUNT()
  - AVG()
  - ORDER BY
- Performing revenue analysis by:
  - Category
  - Age group
  - Subscription status
  - Gender

SQL was used for deep business analysis and metric calculation.

 4️⃣ Power BI (Dashboard Visualization)

After SQL analysis:
- Loaded processed data into Power BI
- Created an interactive dashboard
- Added filters for:
  - Subscription Status
  - Gender
  - Category
  - Shipping Type

Dashboard includes:
- Total Customers
- Average Revenue Rating
- Average Purchase Amount
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Status Distribution

 📂 Dataset Information

- File Name: customer_shopping_behavior.csv
- Contains customer purchase data including:
  - Age Group
  - Gender
  - Product Category
  - Subscription Status
  - Shipping Type
  - Purchase Amount
  - Quantity

 🎯 Key Insights

- Clothing category generates highest revenue.
- Young Adults contribute most to sales.
- Majority customers are non-subscribers.
- Subscription status influences purchase behavior.
🚀 Conclusion

This project demonstrates an end-to-end data analytics workflow:
CSV → Python Cleaning → SQL Analysis → Power BI Dashboard

It highlights practical skills in data preprocessing, SQL querying, and business dashboard development.
