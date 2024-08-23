# Home-Sales-Analysis
Overview

This project focuses on analyzing home sales data using Apache Spark and PySpark. The dataset includes various features related to home sales, such as prices, number of bedrooms and bathrooms, square footage, and more. The analysis is performed using Spark SQL to gain insights into the housing market trends.

Project Structure
Home_Sales_Analysis.ipynb: The Jupyter Notebook containing the code for loading, processing, and analyzing the home sales data.
home_sales_revised.csv: The CSV file containing the raw home sales data used for analysis.
home_sales_partitioned.parquet: The Parquet file containing the partitioned home sales data by the date_built field.
README.md: This file.
Analysis Steps
Setup Environment:

Install necessary packages including Apache Spark and PySpark.
Set up environment variables for Spark and Java.
Initialize a Spark session.
Data Loading:

Load the home sales data from a CSV file into a Spark DataFrame.
Data Processing:

Perform data cleaning and transformation as necessary.
Create temporary views of the DataFrame for Spark SQL queries.
Analysis:

Calculate the average price of homes based on various criteria (e.g., number of bedrooms, bathrooms, year built).
Cache and uncache tables as needed to optimize queries.
Partition the data by date_built and save it in Parquet format.
Create tables and views from the Parquet data.
Results and Insights:

Derive insights from the data by running SQL queries on the DataFrame views.
Save the results in tables or export them for further use.
Key Queries and Functions
Average Price Analysis: Calculate the average price for homes with specific features (e.g., number of bedrooms, bathrooms, floors).
Partitioning: Partition data by the date_built field to optimize storage and query performance.
Caching: Cache tables to improve the performance of repeated queries.
Saving Data: Save the processed data in Parquet format and create Spark SQL tables from it.
Dependencies
Apache Spark: A unified analytics engine for large-scale data processing.
PySpark: The Python API for Spark.
Jupyter Notebook: An interactive environment for running and writing code.
