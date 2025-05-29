🚀 Project Overview

The goal of this project is to:

Understand customer journeys

Analyze product and customer performance

Identify trends in customer reviews and engagement

Build a dynamic dashboard for decision-making using Power BI

🧱 Tech Stack

SQL: Data extraction, transformation, and loading (ETL)

Power BI: Data visualization and dashboard creation

Python: Data enrichment of customer reviews

CSV/BAK: Raw and enriched data sources

📁 File Structure

File	Description
1 - Marketing Analytics Business Case (Clean).pdf	Documentation outlining the project case and objectives
2.1 dim_customers.sql	SQL script to create and populate the Customers dimension
2.2 dim_products.sql	SQL script to create and populate the Products dimension
2.3 fact_customer_journey.sql	Script for customer journey fact table
2.4 fact_customer_reviews.sql	Script for reviews data
2.5 fact_customer_reviews_enrich.csv	Enriched reviews dataset used in analysis
2.6 fact_engagement_data.sql	Script for customer engagement metrics
3.1 Calendar DAX Script.txt	DAX script to create a calendar table in Power BI
3.2 customer_reviews_enrichment.py	Python script to enrich review data
Dashboard.pbix	Final Power BI dashboard file
PortfolioProject_MarketingAnalytics.bak	Backup of the SQL database used

📌 Key Insights

Customer Segmentation: Based on product interest and engagement.

Product Analysis: Identification of top and underperforming products.

Review Sentiment: Enriched data reveals customer sentiment trends.

Marketing Impact: Visual insights into marketing channel effectiveness.

🛠️ How to Use

Database Setup:

1) Restore the PortfolioProject_MarketingAnalytics.bak SQL backup in SQL Server.

2) Run the provided .sql scripts to create dimension and fact tables.

Data Enrichment:

1) Run the customer_reviews_enrichment.py script if you wish to re-process reviews.

Alternatively, use the provided fact_customer_reviews_enrich.csv.

Power BI Dashboard:

1) Open Dashboard.pbix in Power BI Desktop.

2) Ensure data sources are connected and refresh the model.

