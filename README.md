# Product Sales Performance Analysis
Project Title:
Product Sales Performance Analysis

Dashboard Preview:
![page1](https://github.com/Pujiwara/Pictures/blob/main/Product%20Sales%20Performance_page-0001.jpg)
![page2](https://github.com/Pujiwara/Pictures/blob/main/Product%20Sales%20Performance_page-0002.jpg)

Description:
This case study presents a comprehensive analysis of a synthetic Product Sales Dataset containing 200,000 transaction records across multiple regions in the United States. The project was designed to simulate a real-world business analytics scenario and demonstrate an end-to-end data analytics workflow.
The analysis covers the full pipeline, starting from raw data ingestion and cleaning, followed by PostgreSQL data warehouse design using a star schema, and culminating in an interactive Power BI dashboard. The dashboard enables stakeholders to monitor sales performance, identify high-performing products and regions, and support data-driven business decision-making.

Dataset:
https://www.kaggle.com/datasets/yashyennewar/product-sales-dataset-2023-2024

# Analytical Approach
### Methods
The analysis followed a structured, end-to-end analytics methodology:
- **Data Ingestion**
    Raw CSV data was loaded into PostgreSQL using a dedicated `raw` schema.
- **Data Cleaning & Validation (ETL)**
    Data quality checks and transformations were performed in a `staging` schema, including:
    - Date format standardization
    - Handling missing and invalid values
    - Numeric validation for revenue, profit, and quantity
    - Text normalization for categorical fields
- **Data Warehouse Design**
    A **star schema** was implemented to support analytical queries efficiently:
    - Fact table: `fact_orders`
    - Dimension tables: `dim_dates`, `dim_customers`, `dim_products`
- **Business Intelligence & Visualization**
    The curated data warehouse was connected to Power BI to create an interactive, insight-driven dashboard.

### Dashboard Structure
1. **Summary Overview**
    Key KPIs: Total Revenue, Total Profit, Profit Margin, AOV, Total Orders
    Revenue & Profit trend over time
    Revenue distribution by region
    Revenue by product category
2. **Product & Customer Insights**
    Top 10 products by revenue and profit
    Revenue by sub-category
    Revenue distribution by customer state
    Customer and order-level performance metrics

### Tools
- **PostgreSQL** — Data storage, Data cleaning, validation, transformation, dimensional modeling, ETL processing, and data warehouse implementation
- **Power BI** — Data modeling, DAX calculations, and dashboard visualization

# Key Insight
- Revenue is dominated by the **Electronics** category, contributing over **40% (≈57M)** of total revenue, driven by high-value products such as laptops, smartphones, and wearables.
- The overall **profit margin of 22.15%** indicates a healthy business performance, with opportunities for further optimization.
- The **East region** is the largest revenue contributor (**45M**), followed by the West and Central regions, indicating where marketing and inventory focus should be prioritized.
- **California** stands out as the highest-revenue state, while several states show underperformance and potential for market expansion.
- **Tempur-Pedic Mattress** and **Instant Pot** are the top revenue-generating products, highlighting the strong impact of premium-priced items.
- Certain apparel sub-categories generate relatively low revenue, suggesting possible inefficiencies in product assortment.

# Business Recommendations
- **Focus on High-Value Categories:**
    Allocate more resources to Electronics and high-margin home products to maximize revenue and profitability.
- **Regional Optimization:**
    Strengthen marketing campaigns and inventory availability in the East and West regions while developing targeted growth strategies for underperforming regions.
- **Upselling & Bundling Strategies:**
    Leverage top-selling, high-priced products with complementary add-ons or bundles to increase average order value.
- **Category Rationalization:**
    Review low-performing apparel categories for potential stop-loss decisions, rebranding, or bundling promotions.
- **Geographic Expansion:**
    Develop localized marketing strategies to improve penetration in lower-performing states and reduce over-reliance on top states.
