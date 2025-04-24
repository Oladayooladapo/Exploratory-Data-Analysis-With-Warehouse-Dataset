# Exploratory-Data-Analysis-With-Warehouse-Dataset
This project covers my step-by-step approach in tackling real-life data exercises. A comprehensive collection of SQL scripts for data exploration, analytics, and reporting. These scripts cover various analyses such as database exploration, measures, dimnsions and date, time-based trends, cumulative analytics, segmentation, and more.
This repository contains SQL queries I use to create quick analysis in my tasks. It also contains subqueries and CTEs which can be stored as a view in the database for quick BI and visuals. Each script focuses on a specific analytical theme for SQL queries.

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


# DATABASE EXPLORATION
To understand the structure of the database, I visualise the Entity-Relationship Diagram (ERD) that maps out the tables and their connections. I then proceed to understanding the dimensions and measures in the tables, which sets the foundation of unlimited exploratory of the dataset

Purpose:
    - To explore the structure of the database, including the list of tables and their schemas.
    - To inspect the columns and metadata for specific tables.

Table Used:
    - INFORMATION_SCHEMA.TABLES
    - INFORMATION_SCHEMA.COLUMNS

![WhatsApp Image 2025-04-24 at 4 39 29 PM](https://github.com/user-attachments/assets/c7c4753c-0010-45d0-b28d-eb22a0b126e8)

![Database Exploratory](https://github.com/user-attachments/assets/b429748b-364f-4b74-8aa0-414c984eb375)



# DIMENSIONS EXPLORATION
To identify the unique values and categories in each dimension. Recognising how data might be grouped or segmented for later analysis
SQL functions used:
- DISTINCT
- ORDER BY

# DATE EXPLORATION
Purpose:
    - To determine the temporal boundaries of key data points.
    - To understand the range of historical data.

SQL Functions Used:
    - MIN(), MAX(), DATEDIFF()

# MEASURES EXPLORATION
Purpose:
    - To calculate aggregated metrics (e.g., totals, averages) for quick insights.
    - To identify overall trends or spot anomalies.

SQL Functions Used:
    - COUNT(), SUM(), AVG()

# MAGNITUDE ANALYSIS
Purpose:
    - To quantify data and group results by specific dimensions.
    - For understanding data distribution across categories.

SQL Functions Used:
    - Aggregate Functions: SUM(), COUNT(), AVG()
    - GROUP BY, ORDER BY

# RANKING ANALYSIS
Purpose:
    - To rank items (e.g., products, customers) based on performance or other metrics.
    - To identify top performers or laggards.

SQL Functions Used:
    - Window Ranking Functions: RANK(), DENSE_RANK(), ROW_NUMBER(), TOP
    - Clauses: GROUP BY, ORDER BY

# CHANGE OVER TIME ANALYSIS
Purpose:
    - To track trends, growth, and changes in key metrics over time.
    - For time-series analysis and identifying seasonality.
    - To measure growth or decline over specific periods.

SQL Functions Used:
    - Date Functions: DATEPART(), DATETRUNC(), FORMAT()
    - Aggregate Functions: SUM(), COUNT(), AVG()

# CUMULATIVE ANALYSIS
Purpose:
    - To calculate running totals or moving averages for key metrics.
    - To track performance over time cumulatively.
    - Useful for growth analysis or identifying long-term trends.

SQL Functions Used:
    - Window Functions: SUM() OVER(), AVG() OVER()

# PERFORMANCE ANALYSIS
Purpose:
    - To measure the performance of products, customers, or regions over time.
    - For benchmarking and identifying high-performing entities.
    - To track yearly trends and growth.

SQL Functions Used:
    - LAG(): Accesses data from previous rows.
    - AVG() OVER(): Computes average values within partitions.
    - CASE: Defines conditional logic for trend analysis.

# DATA SEGMENTATION
Purpose:
    - To group data into meaningful categories for targeted insights.
    - For customer segmentation, product categorization, or regional analysis.

SQL Functions Used:
    - CASE: Defines custom segmentation logic.
    - GROUP BY: Groups data into segments.

# PART-TO-WHOLE ANALYSIS
Purpose:
    - To compare performance or metrics across dimensions or time periods.
    - To evaluate differences between categories.
    - Useful for A/B testing or regional comparisons.

SQL Functions Used:
    - SUM(), AVG(): Aggregates values for comparison.
    - Window Functions: SUM() OVER() for total calculations.

# REPORTING
Purpose:
    - This report consolidates key customer metrics and behaviors


    
