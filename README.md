# Customer Behavior Analytics: End-to-End Cloud Data Pipeline

 📌 Project Overview
This project demonstrates a professional data engineering and analytics lifecycle. I built a live data stack connecting Python-based ETL, Cloud Data Warehousing (PostgreSQL), and Business Intelligence (Power BI) to extract actionable insights from customer shopping data.


 🛠️ Tech Stack
* Language: Python (Pandas, SQLAlchemy)
* Database: Neon.com (Serverless PostgreSQL)
* Environment: Google Colab
* Visualization: Power BI Desktop
* SQL Techniques: CTEs, Window Functions, Case Statements, Data Segmentation


 ⚙️ Data Pipeline Workflow

 1. Data Engineering & ETL (Python)
Using 'customer_behavior.ipynb', I performed:
* Data Cleaning: Handled missing values and standardized schema for SQL injection.
* Feature Engineering: Prepared the dataset for relational storage.
* Cloud Integration: Established a secure connection between Google Colab and the Neon PostgreSQL server to automate data migration.

 2. Cloud Data Warehousing (SQL)
With the data hosted on the cloud, I executed 'customer_behavior.sql' to solve 10 critical business questions, including:
* Revenue Analysis: Comparing spend across genders and subscription statuses.
* Customer Segmentation: Categorizing users into 'New', 'Returning', and 'Loyal' tiers using SQL logic.
* Product Performance: Identifying top-rated items and high-performing categories via Window Functions.

 3. Business Intelligence (Power BI)
I connected the Neon Cloud DB to Power BI to create an interactive dashboard:
* Executive KPIs: Total Revenue, Average Ratings, and Subscription Rates.
* Operational Insights: Shipping efficiency analysis (Standard vs. Express) and regional sales distribution.


 📊 Key Insights Captured
* Loyalty Impact: Segmented 3,900+ customers into 3 tiers, identifying purchase frequency patterns.
* Shipping Behavior: Validated correlations between shipping tiers and purchase amounts.
* Subscription Value: Analyzed the revenue contribution of subscribed vs. non-subscribed users.


 📂 File Structure
* customer_behavior.ipynb: Python script for ETL and Cloud DB connection.
* customer_behavior.sql: The full library of 10 business logic queries.
* customer_behavior_dashboard.pbix: The Power BI visualization file.
* customer_shopping_behavior.csv: The raw dataset.


 🚀 How to Use
1. Run the Python notebook to view the ETL and database connection process.
2. Import the SQL file into a PostgreSQL environment to test business logic queries.
3. Open the `.pbix` file to explore the interactive data visualizations.

 Dashboard Preview:
(customer_behavior_dash.png)
