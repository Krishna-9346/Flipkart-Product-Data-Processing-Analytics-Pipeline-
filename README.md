## Project Overview
This project focuses on building a scalable data processing pipeline using PySpark on Databricks to analyze Flipkart product data.
The objective is to clean raw e-commerce data and extract insights related to product ratings, customer engagement, pricing trends, and fulfillment impact.
# Problem_statment
Flipkart hosts a wide range of products across categories with varying prices and customer ratings.
Understanding how price, category, fulfillment, and star ratings influence customer engagement is crucial for business decision-making.
# Dataset Description
The dataset contains Flipkart product details including:
- Product ID and title
- Product category (Men/Women)
- Platform information
- Actual product price
- Product rating
- Number of ratings and reviews
- Star-wise rating distribution (1–5 stars)
- Fulfillment status
# Tech Stack
- Python
- PySpark
- Apache Spark
- Databricks
- GitHub
# ETL Pipeline Explanation
Extract:
- Loaded Flipkart product data (CSV) into Databricks

Transform:
- Handled missing and invalid values
- Converted columns to appropriate data types
- Created derived columns such as price_range
- Aggregated ratings, reviews, and engagement metrics

Load:
- Generated analytics-ready datasets
- Displayed insights using Spark transformations and actions
  ## Databricks Job Execution Flow
  - Uploaded PySpark notebook to Databricks workspace
- Attached notebook to Spark cluster
- Successfully executed transformations and aggregations
- Validated outputs using Spark DataFrame actions

