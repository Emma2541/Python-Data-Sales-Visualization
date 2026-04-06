# Python-Data-Sales-Visualization
An end-to-end data pipeline built in Colab to merge, clean, and analyze sales data. 

📌 Overview

This project demonstrates an end-to-end data analysis workflow using Python and MySQL. The goal was to simulate a real-world e-commerce scenario by building a database, extracting data, and analyzing sales performance to generate meaningful business insights.

🎯 Objectives
Load and process structured e-commerce data
Perform data cleaning and transformation
Analyze sales trends and customer behavior
Visualize key insights for decision-making

🛠️ Tools & Technologies
Python
Pandas
NumPy
Matplotlib

⚙️ Project Workflow
1. Database Setup
Installed and configured MySQL in Google Colab
Created a database (ECommerceDB)
Executed SQL scripts to create and populate tables
2. Data Extraction
Connected Python to MySQL using SQLAlchemy
Loaded multiple tables:
Orders
OrderDetails
Products
Categories
Calendar
3. Data Cleaning & Transformation
Converted data types (e.g., numeric values)
Merged multiple tables into a single dataset
Created new features such as:
Sales = Quantity × UnitPrice
4. Data Analysis
Created pivot tables for sales by category and month
Performed customer segmentation (Low, Medium, High)
Generated cross-tab analysis for order frequency
Analyzed time-based sales trends
5. Data Visualization
Line chart for monthly sales trends
Bar charts for:
Top product categories
Top 10 products
Pie chart showing monthly sales distribution

📊 Key Insights
Identified top-performing product categories
Detected monthly sales trends and seasonality
Segmented customers based on spending behavior
Highlighted the most frequently ordered categories by day

python graduation_project.py
Ensure MySQL is installed and running locally.
🚀 Conclusion

This project highlights the ability to work with databases, perform data analysis, and extract actionable insights using Python. It reflects practical skills in handling real-world datasets and building data-driven solutions.
