🛒 Customer Shopping Behavior Analysis
📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to uncover insights into spending patterns, customer segments, product preferences, discount usage, and subscription behavior to support data-driven business decisions.

The project follows a complete analytics workflow:

Data cleaning & feature engineering (Python)

Business analysis (SQL – PostgreSQL)

Interactive visualization (Power BI)

🎯 Objectives

Analyze customer purchasing behavior and preferences

Identify high-value customer segments

Evaluate the impact of discounts and subscriptions

Discover top-performing products and categories

Provide actionable business recommendations

📂 Dataset Summary

Records: 3,900 transactions

Features: 18 columns

Key Data Fields

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping Behavior: Discount Applied, Previous Purchases, Purchase Frequency

Feedback & Logistics: Review Rating, Shipping Type

📌 Missing Values:

37 missing values in Review Rating, handled during preprocessing.

🛠️ Tech Stack

Python: Pandas, NumPy

SQL: PostgreSQL

Visualization: Power BI

Environment: Jupyter Notebook

🔍 Exploratory Data Analysis (Python)

The Python notebook focuses on data preparation and exploratory analysis:

Loaded and inspected data structure (info(), describe())

Handled missing values using median imputation by product category

Standardized column names using snake_case

Feature engineering:

Created age_group by binning customer ages

Derived purchase frequency–based features

Identified redundant columns and removed them

Loaded cleaned data into PostgreSQL for SQL analysis

🧮 Data Analysis (SQL – Business Questions)

Using PostgreSQL, the following business questions were answered:

Revenue comparison by gender

High-spending customers who used discounts

Top 5 products by average review rating

Average purchase amount by shipping type

Subscriber vs non-subscriber revenue comparison

Products most dependent on discounts

Customer segmentation (New, Returning, Loyal)

Top 3 products within each category

Relationship between repeat purchases and subscriptions

Revenue contribution by age group

📊 Dashboard (Power BI)

An interactive Power BI dashboard was built to visualize:

Revenue trends and customer segments

Product and category performance

Subscription and discount impact

Shipping behavior insights

The dashboard enables stakeholders to quickly identify high-value customers and growth opportunities.

💡 Key Insights

Subscribers generate higher average revenue than non-subscribers

Loyal customers contribute a significant share of total sales

Discounts increase volume but require margin optimization

Express shipping users show higher purchase values

Certain products are highly discount-dependent

📈 Business Recommendations

Promote subscription benefits to improve retention

Implement customer loyalty programs

Optimize discount strategies to balance revenue and margins

Highlight top-rated and best-selling products

Focus marketing efforts on high-revenue age groups

🚀 Future Enhancements

Add predictive models (churn, customer lifetime value)

Automate ETL pipeline

Enhance dashboard with real-time data

Deploy insights via a web app (Streamlit / Flask)

👤 Author

Diwanshu Sharma
Aspiring Data Scientist | Data Analytics & Machine Learning
