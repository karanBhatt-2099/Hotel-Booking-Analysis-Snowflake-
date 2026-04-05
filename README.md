# Hotel-Booking-Analysis-Snowflake-
📌 Overview
This project demonstrates working with hotel booking data in Snowflake using the Medallion Architecture (Bronze → Silver → Gold). It includes loading raw CSV data, cleaning and standardizing records, and transforming them into analytics-ready datasets using SQL, along with a Snowsight dashboard for insights.

🏗️ Architecture
🥉 Bronze Layer
Raw CSV data loaded into Snowflake stages
Data stored without transformations

🥈 Silver Layer
Data cleaning and validation:
Handle missing values
Fix invalid emails
Remove negative pricing
Correct date inconsistencies
Standardize status values

🥇 Gold Layer
Aggregated and business-ready datasets
Optimized for reporting and analysis

🔧 Key Features
Load raw data using Snowflake stages
Data cleaning and validation using SQL
Handle inconsistent and corrupted data
Transform data into structured formats
Build analytics-ready datasets
Create interactive dashboards in Snowsight

🧰 Tech Stack
Snowflake
Snowflake SQL
Snowsight Dashboards
File Formats, Stages & COPY INTO
Medallion Architecture

Conclusion

This project highlights how Snowflake can be used end-to-end for data processing and analytics, following industry best practices and delivering meaningful business insights.

