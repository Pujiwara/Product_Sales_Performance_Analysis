# Product_Sales_Performance_Analysis
Project Title:
Product Sales Performance Analysis

Dashboard Preview:
![page1](https://github.com/Pujiwara/Pictures/blob/main/Product%20Sales%20Performance_page-0001.jpg)
![page2](https://github.com/Pujiwara/Pictures/blob/main/Product%20Sales%20Performance_page-0002.jpg)

Description:
This project is a comprehensive analysis of the Product Sales Dataset. This dataset contains 200,000 synthetic sales records simulating real-world product transactions across different U.S. regions.
The main goal of this project is to build a complete end-to-end analytics pipeline, starting from PostgreSQL data warehouse design, ETL transformations, and culminating in an interactive Power BI dashboard for business insight exploration.

Tools Used:
PostgreSQL, 
Power BI

Key Insights:
1. Revenue is led by the Electronics category (40%+ or 57M). High-value products such as laptops, smartphones, and wearables contribute to nearly half of the total revenue.
2. The largest revenue contributor is the East region (45M). Marketing and inventory strategies should prioritize the East and West regions.
3. The top products by revenue are the Tempur-Pedic Mattress and Instant Pot. These high-priced items generate significant revenue and can be leveraged through upselling strategies.
4. The profit margin of 22.15% is relatively stable. The business is performing well but can further improve by focusing on high-margin categories (bedding, mattresses).
5. California is the highest-revenue state. There is potential to expand into lower-performing states.
6. Several apparel categories generate low revenue (Kids Wear, Bags, Wearable Accessories). These small categories can be evaluated for: stop-loss decisions, rebranding, or bundling promotions.

Dataset:
https://www.kaggle.com/datasets/yashyennewar/product-sales-dataset-2023-2024

Data Warehouse Star Schema Components:
fact_orders, 
dim_dates, 
dim_customers, 
dim_products

Key steps in the ETL workflow include:
1. Standardizing date formats
2. Data cleaning and validation
3. Key mapping between fact and dimension tables

Power BI Dashboard Structure:
The dashboard is organized into two main pages:
1. Summary Overview
2. Customer and Product Insight
