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
10. Part-to-Whole
11. Data segmentation
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

# 


    
