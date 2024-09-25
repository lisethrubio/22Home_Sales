# 22Home_Sales


## Overview

This project requires using *`PySpark SQL`* to analyze home sales data and extract key metrics. The goal is to answer business-related questions about average home prices based on specific criteria, implement caching and partitioning, and evaluate query performance on cached versus uncached data. There are three main parts.


## Repository and Data Setup

A new GitHub repository named `"Home_Sales"` is created and cloned locally. The provided files are downloaded, and the dataset (`"home_sales_revised.csv"`) is read into a *`PySpark`* DataFrame. A temporary SQL table called `"home_sales"` is created from this data.

## SQL Queries and Caching

Several *`SparkSQL`* queries are executed to determine average home prices based on different conditions. The `"home_sales"` table is cached to improve query performance, and the runtime of cached versus uncached queries is compared.

## Data Partitioning and Uncaching

The data is partitioned by the `"date_built"` field and saved in Parquet format. A temporary table is created from this partitioned data, and performance comparisons are made. The `"home_sales"` table is then uncached, and its uncaching status is verified.


## References

- Xpert Learning Assistant
- AskBCS Learning Assistant
- Curriculum content
- Tutoring