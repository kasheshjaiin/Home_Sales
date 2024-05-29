# Home Sales Data Analysis with SparkSQL

This project demonstrates the use of SparkSQL for analyzing home sales data.

## Overview

In this project, we use PySpark and SparkSQL to analyze a dataset containing home sales information. We perform various data manipulation and analysis tasks to extract insights from the data.

## Contents

1. Data Loading
2. Data Analysis
3. Performance Comparison

## Data Loading

We load the home sales data from an AWS S3 bucket into a Spark DataFrame using PySpark.

## Data Analysis

Using SparkSQL, we perform the following analysis tasks:
- Calculate the average price for a four-bedroom house sold per year.
- Determine the average price of a home for each year the home was built, with specific criteria.
- Partition the data by the "date_built" field.
- Cache the temporary table for faster query execution.
- Analyze the average price of a home per "view" rating with specific conditions.

## Performance Comparison

We compare the runtime of the queries with and without caching and analyze the impact of partitioning on query performance.

## Requirements

- Apache Spark
- Python (with PySpark)
- Jupyter Notebook or Google Colab (optional)

## How to Run

1. Install Apache Spark on your system.
2. Clone this repository.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Run each cell to execute the code.
