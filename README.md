# Exploratory-Data-Analysis-With-Warehouse-Dataset
A Hands-on Approach to Real-world SQL Analytics
Welcome! This repository demonstrates my structured approach to data exploration and analysis using SQL on a warehouse-themed dataset. It’s designed to showcase how I translate raw data into actionable insights through a collection of analytical themes.

# Project Overview
This project reflects how I typically tackle real-world business data problems, especially within data warehouse environments. Each SQL script captures a unique stage or lens of analysis, from understanding database structure to answering specific business questions using advanced SQL techniques.

Rather than running monolithic queries, I break down analysis into modular, reusable scripts that mimic how insights are generated in professional analytics workflows—particularly when supporting BI dashboards, KPIs, and operational reports.

# What's Inside?
The repository includes SQL scripts that cover:

Data Exploration & Profiling

Descriptive & Diagnostic Analytics

Time-based Trends and Comparisons

Segmented and Aggregated Reporting

Views, Subqueries, and CTEs designed for dashboard integration

These queries can easily be stored as views in a relational database to feed Power BI, Tableau, or other reporting platforms.

# WORKFLOW
1. Database Exploration
2. Dimensions Exploration
3. Date Exploration
4. Measures Exploration
5. Magnitude
6. Ranking
7. Change over time
8. Cummulative Analysis
9. Performance Analysis
10. Data segmentation
11. Part-to-whole Analysis
12. Reporting


# Database Exploration
To understand the structure of the database, I visualise the Entity-Relationship Diagram (ERD) that maps out the tables and their connections. I then proceed to understanding the dimensions and measures in the tables, which sets the foundation of unlimited exploratory of the dataset

Purpose:
    - To explore the structure of the database, including the list of tables and their schemas.
    - To inspect the columns and metadata for specific tables.

Table Used:
    - INFORMATION_SCHEMA.TABLES
    - INFORMATION_SCHEMA.COLUMNS

![WhatsApp Image 2025-04-24 at 4 39 29 PM](https://github.com/user-attachments/assets/c7c4753c-0010-45d0-b28d-eb22a0b126e8)

![Database Exploratory](https://github.com/user-attachments/assets/b429748b-364f-4b74-8aa0-414c984eb375)



# Dimensions Exploration
To identify the unique values and categories in each dimension. Recognising how data might be grouped or segmented for later analysis
SQL functions used:
- DISTINCT
- ORDER BY

# Date Exploration
Purpose:
    - To determine the temporal boundaries of key data points.
    - To understand the range of historical data.

SQL Functions Used:
    - MIN(), MAX(), DATEDIFF()

# Measures Exploration
Purpose:
    - To calculate aggregated metrics (e.g., totals, averages) for quick insights.
    - To identify overall trends or spot anomalies.

SQL Functions Used:
    - COUNT(), SUM(), AVG()

# Magnitude Analysis
Purpose:
    - To quantify data and group results by specific dimensions.
    - For understanding data distribution across categories.

SQL Functions Used:
    - Aggregate Functions: SUM(), COUNT(), AVG()
    - GROUP BY, ORDER BY

# Ranking Analysis
Purpose:
    - To rank items (e.g., products, customers) based on performance or other metrics.
    - To identify top performers or laggards.

SQL Functions Used:
    - Window Ranking Functions: RANK(), DENSE_RANK(), ROW_NUMBER(), TOP
    - Clauses: GROUP BY, ORDER BY

# Change Over Time Analysis
Purpose:
    - To track trends, growth, and changes in key metrics over time.
    - For time-series analysis and identifying seasonality.
    - To measure growth or decline over specific periods.

SQL Functions Used:
    - Date Functions: DATEPART(), DATETRUNC(), FORMAT()
    - Aggregate Functions: SUM(), COUNT(), AVG()

# Cummulative Analysis
Purpose:
    - To calculate running totals or moving averages for key metrics.
    - To track performance over time cumulatively.
    - Useful for growth analysis or identifying long-term trends.

SQL Functions Used:
    - Window Functions: SUM() OVER(), AVG() OVER()

# Performance Analysis
Purpose:
    - To measure the performance of products, customers, or regions over time.
    - For benchmarking and identifying high-performing entities.
    - To track yearly trends and growth.

SQL Functions Used:
    - LAG(): Accesses data from previous rows.
    - AVG() OVER(): Computes average values within partitions.
    - CASE: Defines conditional logic for trend analysis.

# Data Segmentation
Purpose:
    - To group data into meaningful categories for targeted insights.
    - For customer segmentation, product categorization, or regional analysis.

SQL Functions Used:
    - CASE: Defines custom segmentation logic.
    - GROUP BY: Groups data into segments.

# Part-To-Whole Analysis
Purpose:
    - To compare performance or metrics across dimensions or time periods.
    - To evaluate differences between categories.
    - Useful for A/B testing or regional comparisons.

SQL Functions Used:
    - SUM(), AVG(): Aggregates values for comparison.
    - Window Functions: SUM() OVER() for total calculations.

# Reporting
Purpose:
    - This report consolidates key customer metrics and behaviors
    
#  Use Cases
These scripts are ideal for:

Showcasing SQL mastery for technical interviews and portfolios

Building out BI dashboards from warehouse data

Supporting business decisions with segmented performance reports

Laying the foundation for more advanced modeling in data science pipelines

#  Final Note
This is more than just a collection of SQL snippets—it's a showcase of my thought process as a data analyst. Each file tells part of a story: how we understand business data, shape it for decision-making, and build scalable, insightful solutions.




    
