# Sales Data Analytics Pipeline

An end-to-end sales data analytics project built using Python, MySQL, SQL and Power BI.

## Business Problem

Raw sales data stored in Excel can contain inconsistent or unclean data, making it difficult to analyze sales performance, profitability and regional trends.

The objective of this project was to build a simple end-to-end data pipeline that transforms raw sales data into a structured database and an interactive Power BI dashboard for business analysis.

## Project Workflow

Excel Raw Data
↓
Python Data Cleaning
↓
MySQL Database
↓
SQL Analysis
↓
Power BI Dashboard

## Tools & Technologies

- Python
- Pandas
- MySQL
- SQL
- Power BI
- Excel

## Data Cleaning – Python

Python and Pandas were used to prepare the raw sales data for analysis.

Key steps included:
- Data cleaning and preprocessing
- Handling data inconsistencies
- Data type formatting
- Creating required Year and Month fields
- Preparing the cleaned dataset for database storage

## Database – MySQL

The cleaned dataset was stored in a MySQL database named `salesdb`.

The `sales_data` table contains sales-related fields including:

- Order ID
- Order Date
- Customer
- Region
- Product
- Sales
- Cost
- Profit
- Year
- Month

The final dataset contains 682 records.

## SQL Analysis

SQL queries were used to analyze the stored sales data and generate business-level information such as:

- Sales by region
- Profit by region
- Monthly sales trends
- Product-wise sales performance
- Overall sales and profit metrics

## Power BI Dashboard

An interactive Power BI dashboard was created to visualize sales performance.

### Dashboard Features

- Total Sales
- Total Profit
- Average Profit Percentage
- Monthly Sales Trend
- Profit by Region
- Sales by Product
- Region and Year filters

## Project Outcome

The project demonstrates an end-to-end data analytics workflow, from raw Excel data cleaning to database storage, SQL analysis and interactive Power BI visualization.

## Key Skills Demonstrated

Python | Pandas | Data Cleaning | MySQL | SQL | Power BI | Data Visualization | Data Analytics
