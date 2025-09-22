# Walmart Sales Data Analysis
This project provides a comprehensive analysis of Walmart sales data. The goal is to extract valuable business insights from raw data, including customer behavior, product performance, and branch-specific metrics. The entire workflow, from data cleaning and transformation (ETL) to database querying and visualization, is documented in this repository.

## Project Workflow
The project follows a standard data analytics workflow, broken down into the following key phases:

Data Extraction & Transformation (ETL): Raw data is extracted, cleaned, and transformed into a structured format ready for analysis.

Database Loading & Querying: The cleaned data is loaded into a MySQL database, and analytical queries are executed to answer specific business questions.

Data Visualization: The insights derived from the SQL queries are visualized using business intelligence tools to make them easily understandable for stakeholders.


## Key Business Questions & Insights
The SQL queries in walmart_queries.sql were crafted to answer the following questions:

Payment Method Analysis: What are the most popular payment methods, and how do they differ across branches?

Customer & Product Rating: Which product categories are the highest-rated in each branch?

Operational Efficiency: Which are the busiest days and times of day for each branch?

Profitability: How does gross income vary by product category, and which categories are the most profitable?

Revenue Trends: How has revenue changed over time, specifically identifying branches with a significant decrease in revenue year-over-year?

## Visualizations
The final step of the analysis involved creating visualizations to present the findings in a clear and intuitive way. The dashboards below, created using Excel and Power BI, were used to present key metrics like total sales, quantity, and profit, as well as granular insights into sales by category, profit by state, and average delivery time.

These visualizations are a powerful way to communicate the results of the data analysis and help business decision-makers quickly grasp the key performance indicators and trends.

Note: The Python ETL script uses an in-memory database (sqlite3) for demonstration purposes. For a large-scale project, you would use a connection to a permanent database like MySQL or PostgreSQL.
<img width="1304" height="736" alt="image" src="https://github.com/user-attachments/assets/123b96f5-f9b8-4a67-bd58-b7860338e9a0" />
More optimised Dashboard
<img width="1287" height="724" alt="Screenshot 2025-09-22 181418" src="https://github.com/user-attachments/assets/0a4dfb08-db03-48ff-8cf1-c869bbc9f278" />
