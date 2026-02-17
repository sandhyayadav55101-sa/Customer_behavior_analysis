# Customer_behavior_analysis
Data Analytics project showcasing customer behavior analysis using python, sql and power bi
Customer Shopping Behavior Analysis

End-to-End Data Analytics Project
#Overview
This project presents a complete end-to-end data analytics workflow focused on analyzing customer shopping behavior. The objective is to transform raw transactional data into actionable business insights using Python, PostgreSQL, and Power BI.
The project demonstrates practical skills in data cleaning, exploratory data analysis (EDA), SQL-based querying, and business intelligence dashboard development — aligning with real-world data analyst responsibilities.

# Dataset
File: customer_shopping_behavior.csv
Type: Transactional retail dataset
Contents include:
Customer information
Product categories
Purchase amounts
Payment methods
Purchase dates
Location details
The dataset was processed to ensure data integrity before analysis.

 #Tools & Technologies
Tool	Purpose
Python (Pandas, NumPy)	Data cleaning & transformation
Matplotlib / Seaborn	Exploratory Data Analysis (EDA)
PostgreSQL	Structured querying & aggregation
Power BI	Interactive dashboard development
Jupyter Notebook	Analysis environment

#Methodology & Workflow
1️Data Collection & Loading
Imported CSV data using Pandas.
Inspected dataset structure and summary statistics.

#Data Cleaning & Preprocessing
Handled missing values.
Removed duplicate records.
Standardized column formats.
Corrected inconsistent data types.
Validated numeric fields for accuracy.

 #Exploratory Data Analysis (EDA)
Performed statistical and visual analysis to identify:
Revenue distribution
Customer spending patterns
Popular product categories
Payment method preferences
Monthly sales trends
Location-wise performance

#SQL Analysis (PostgreSQL)
Loaded cleaned dataset into PostgreSQL.
Executed complex queries using:
GROUP BY
JOIN
Aggregate functions
Date-based filtering
Generated insights such as:
Top customers by revenue
Category-wise sales performance
Monthly and regional revenue trends
(SQL script available: sql.sql)

# Power BI Dashboard Development
Designed an interactive dashboard including:
KPI Cards (Total Revenue, Total Transactions, Average Purchase Value)
Sales by Category
Sales Trend Over Time
Payment Method Distribution
Regional Performance Analysis
Customer Insights
Power BI file: Customer behavior dashboard.pbix

# Dashboard Highlights
Interactive slicers and filters
Dynamic revenue trend visualization
Drill-down capability for deeper insights
Clean and business-focused layout
Executive-level summary view

# Key Insights & Results
Identified highest revenue-generating product categories.
Detected seasonal trends in customer purchasing behavior.
Recognized top-performing regions.
Determined preferred payment methods.
Highlighted high-value customer segments.
These insights can support strategic decision-making in marketing, inventory planning, and customer retention.

# How to Run the Project
1. Clone the Repository
git clone <repository-link>
cd <project-folder>

2. Install Dependencies
pip install pandas numpy matplotlib seaborn psycopg2

3. Run Python Analysis
Open Jupyter Notebook
Execute EDA and cleaning scripts

4. Setup PostgreSQL
Create a database
Import cleaned dataset
Run queries from sql.sql

5. Open Power BI Dashboard
Open Customer behavior dashboard.pbix
Refresh data connection if required
