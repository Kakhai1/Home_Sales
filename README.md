# Spark SQL Data Analysis with AWS S3 and Parquet

This GitHub repository contains Python code that demonstrates data analysis using Spark SQL with data stored in an AWS S3 bucket. It covers various SQL queries and operations performed on the dataset, including caching and working with Parquet formatted data. The code also measures the runtime of different operations for performance evaluation.

## Overview

Apache Spark is a powerful data processing framework that can handle large datasets efficiently. This repository showcases how to work with Spark SQL to perform data analysis on a dataset of home sales.

### Features

- Data ingestion from an AWS S3 bucket.
- Creating temporary views of the data.
- Executing SQL queries to answer specific questions about the dataset.
- Caching and uncaching temporary tables to compare performance.
- Working with Parquet formatted data.
- Timing and comparing the runtime of SQL operations.

## Usage

To use this code, follow the instructions below:

1. **Set Up the Environment:** Ensure you have the necessary environment for Spark and Java installed.

2. **Read Data from AWS S3:**
   - The code reads data from an AWS S3 bucket and creates a temporary view of the dataset.

3. **Run SQL Queries:**
   - Execute SQL queries to find information about the dataset, such as average prices for specific property criteria and "view" ratings.

4. **Cache Data:**
   - Demonstrate the caching of the temporary table and check if the table is cached.

5. **Performance Comparison:**
   - Compare the runtime of SQL queries with and without caching the data.

6. **Parquet Data:**
   - Write the DataFrame as a Parquet file partitioned by the "date_built" field and perform SQL operations on it.

7. **Uncache Data:**
   - Uncache the temporary table and check if it's no longer cached.

## Repository Structure
