# 🛒 Customer Shopping Behavior Analysis

This project analyzes customer shopping behavior using transactional data to uncover insights into spending patterns, customer segments, product preferences, discount usage, and subscription behavior for better business decision-making.

---

## 📌 Project Overview
The goal of this project is to:
- Analyze customer purchasing behavior across product categories
- Identify high-value and loyal customer segments
- Study the impact of discounts and subscriptions on revenue
- Discover top-performing products and categories
- Provide actionable business recommendations

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- SQL (PostgreSQL)
- Power BI
- Jupyter Notebook

---

## 📂 Dataset
- **Records:** 3,900 customer transactions
- **Features:** 18 columns including:
  - Customer demographics (Age, Gender, Location, Subscription Status)
  - Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color)
  - Shopping behavior (Discount Applied, Previous Purchases, Purchase Frequency)
  - Customer feedback (Review Rating)
  - Shipping details (Shipping Type)

📌 **Missing Values:**
- Review Rating column contained missing values, handled during preprocessing.

---

## 🔍 Exploratory Data Analysis (Python)
The following steps were performed using Python:
- Data loading and structure inspection
- Summary statistics and missing value analysis
- Median-based imputation for missing review ratings (category-wise)
- Feature engineering:
  - Created `age_group` from customer age
  - Derived purchase frequency features
- Standardized column naming for consistency
- Removed redundant columns
- Loaded cleaned data into PostgreSQL for SQL analysis

---

## 🧮 Data Analysis (SQL)
Business-focused SQL queries were written to answer key questions:
- Revenue contribution by gender
- Identification of high-spending discount users
- Top 5 products by average review rating
- Comparison of average purchase amount by shipping type
- Subscriber vs non-subscriber revenue analysis
- Products most dependent on discounts
- Customer segmentation (New, Returning, Loyal)
- Top 3 products within each category
- Relationship between repeat purchases and subscriptions
- Revenue contribution by age group

---

## 📊 Dashboard (Power BI)
An interactive Power BI dashboard was created to visualize:
- Revenue trends and customer segments
- Product and category performance
- Discount and subscription impact
- Shipping behavior insights

---

## 💡 Key Insights
- Subscribers generate higher average revenue than non-subscribers
- Loyal customers contribute a significant share of total sales
- Discounts increase sales volume but impact margins
- Express shipping customers tend to spend more
- Certain products rely heavily on discounts to drive sales

---

## 📈 Business Recommendations
- Promote subscription plans with exclusive benefits
- Implement loyalty programs for repeat customers
- Optimize discount strategies to balance revenue and profit
- Highlight top-rated and best-selling products in campaigns
- Focus marketing efforts on high-revenue age groups

---

## 🚀 Future Improvements
- Build predictive models (churn, customer lifetime value)
- Automate ETL and reporting pipeline
- Enhance dashboard with real-time data
- Deploy insights using Streamlit or Flask

---

## 👤 Author
**Diwanshu Sharma**  
Aspiring Data Scientist | Data Analytics & Machine Learning
