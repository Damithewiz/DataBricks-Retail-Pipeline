# DataBricks-Retail-Pipeline

## Project Objective
This project simulates an end-to-end retail data pipeline on Databricks, showcasing the use of Delta Lake, PySpark, and SQL for efficient data processing, transformation, and analytics. It demonstrates how modern big data tools can be used to extract actionable insights from raw transactional data.

## Key Features
- End-to-end data pipeline built on Databricks using Delta Lake architecture (Bronze, Silver, Gold).
- Processed a synthetic retail transaction dataset to generate business-ready insights.
- Integrated PySpark for feature engineering, SQL for business KPI calculation, and Matplotlib for exploratory visualization.
- Applied advanced data transformations and stored output as optimized Delta tables.
- Demonstrated scalable big data practices suitable for real-world data analytics environments.

## Insights Uncovered
- Fridays and Saturdays recorded the highest total revenue, aligning with weekend shopping trends.
- Cash on Delivery had the second-highest transaction volume and total revenue, and the highest Average Order Value, indicating a strong spending tendency among COD users.
- Card remained the most frequently used payment method overall.
- Certain product categories consistently generated higher revenue, indicating top-selling verticals.
- High discount transactions (>25%) resulted in higher average spend per order.

## Tools & Technologies
- Databricks Community Edition as platform for distributed data processing, notebook orchestration, and collaborative development.
- Delta Lake for reliable data storage across Bronze, Silver, and Gold layers.
- PySpark (DataFrames & SQL) for large-scale data cleaning, transformation, and feature engineering.
- SQL for business KPI derivation and analytical querying.
- Matplotlib for visual exploration and generation of insights.
- Databricks Jobs for pipeline automation and scheduled execution.

## Future Improvements
- Integrate orchestration using Databricks Workflows or Jobs.
- Add streaming support via Auto Loader or Spark Structured Streaming.
- Deploy dashboards using Power BI or Tableau connectors.
