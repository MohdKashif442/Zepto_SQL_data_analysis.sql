# Zepto SQL Data Analysis Project

This project performs end-to-end data analysis using SQL on a dataset inspired by Zepto, a fast delivery e-commerce grocery platform. The goal is to clean the data, explore insights, and answer specific business questions using SQL queries.

## 📁 Files Included

- `zepto_v2.csv`: Raw dataset containing product-level details such as SKU, price, stock, weight, etc.
- `Zepto_SQL_data_analysis.sql`: SQL script that performs:
  - Table creation and schema setup
  - Data exploration and cleaning
  - Business-centric queries to derive insights

## 🧹 Key Tasks Performed

- **Data Cleaning**:
  - Removed products with zero price
  - Converted paise to rupees
  - Checked for nulls and duplicates

- **Exploratory Data Analysis**:
  - Unique categories, out-of-stock stats
  - High MRP but unavailable items
  - Best-value products by discount

- **Business Insights**:
  - Estimated revenue by category
  - Top 5 categories by average discount
  - Price per gram for better value evaluation
  - Inventory segmentation by weight class

## 📊 Sample Questions Answered

- What are the top 10 best-value products by discount percentage?
- Which high-MRP products are out of stock?
- What’s the estimated revenue per category?
- Which categories offer the best average discounts?
- How is inventory distributed by weight?

## 🚀 Tools Used

- PostgreSQL (or any standard SQL database)
- SQL for all logic and analysis

---

## 📌 How to Use

1. Import the `zepto_v2.csv` dataset into your SQL environment (or use any SQL-compatible ETL tool).
2. Run the `Zepto_SQL_data_analysis.sql` file step-by-step.
3. Modify queries to extract more insights.

