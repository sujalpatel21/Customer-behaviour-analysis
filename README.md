📊 Customer Behaviour Analysis – End-to-End Data Analytics Project

Tools Used: MySQL, Python (Pandas/Matplotlib/Seaborn), Power BI, Excel
Focus: Customer behaviour trends, sales insights, segmentation, business recommendations

🧠 1. Project Overview

This project is an end-to-end customer behaviour analysis designed to help businesses understand how customers interact with their products, what drives sales, and which customer segments are most valuable.
The analysis covers the full analytics pipeline:
Data understanding
Data cleaning & transformation
Exploratory data analysis (EDA)
SQL querying for insights
Visualization in Power BI
Business insights & actionable recommendations

This project demonstrates real-world data analyst capabilities, including analytical thinking, BI dashboarding, SQL expertise, and storytelling.

🎯 2. Business Problem

Companies often have large datasets but struggle to answer key questions:
Which customer segment contributes the most revenue?
What patterns exist in customer purchases?
What factors influence high-value customers?
How does customer behaviour change over time?
Which products/regions need business attention?

This project solves these questions using data-driven exploration and modelling.

🛠️ 3. Tech Stack & Skills Demonstrated
🔹 Database (MySQL)

SQL queries for filtering, grouping, aggregations
Joins across customer, transaction, and product tables
Creating analytical datasets from raw transactional data

🔹 Python

Data cleaning (missing values, duplicates, formatting)
Feature creation (RFM scores, segmentation fields)
Exploratory visualizations (histograms, heatmaps, distribution analysis)

🔹 Power BI

Interactive dashboard creation
KPI cards, trend lines, and heatmaps
Customer segmentation visuals
Drill-through reports

🔹 Data Analytics Skills

EDA (Exploratory Data Analysis)
Segmentation
Business storytelling
Insight generation
Reporting & dashboarding

🧹 4. Data Cleaning & Transformation (Python)

Key cleaning steps included:
Removing duplicates and null records
Converting inconsistent date formats
Standardizing categorical values
Creating calculated fields
Total Spend
Purchase Frequency
Recency (days since last purchase)

Example transformation:
df['Customer_Name'] = df['Customer_Name'].str.strip().str.title()
df['Email'] = df['Email'].str.lower()
df['Amount'] = df['Amount'].replace('[^0-9.]','', regex=True).astype(float)

🧮 5. SQL Analysis (MySQL)

A dedicated MySQL database was created to perform analytical queries.
Example Questions Answered Using SQL:
Who are our top-spending customers?
What is the average order value by customer segment?
Which product categories sell the most?
How does purchase frequency vary across regions?
Which time period generates highest revenue?

Sample SQL Query:
SELECT 
    CustomerID,
    COUNT(OrderID) AS Total_Orders,
    SUM(Amount) AS Total_Revenue,
    AVG(Amount) AS Avg_Order_Value
FROM sales_data
GROUP BY CustomerID
ORDER BY Total_Revenue DESC
LIMIT 10;

📈 6. Exploratory Data Analysis (EDA)

Visual patterns were discovered using Python:
Distribution of customer spending
Frequency of purchases
Outlier detection

These insights helped identify key behaviour traits of loyal and high-value customers.

📊 7. Power BI Dashboard

A professional interactive dashboard was created with:
KPIs: Total Revenue, Avg Purchase, Retention Metrics
Customer Segmentation Charts
Purchase Frequency Visuals
Top Products & Regions
Trend Analysis Over Months
The dashboard turns raw data into actionable business intelligence.

🧠 8. Key Insights

Some major insights discovered (example):

🏆 20% of customers contributed nearly 60% of total revenue.
📅 Highest purchasing activity observed in Q3.
🎯 Customers aged 25–35 showed highest repeat purchase rate.
🛒 Product category Electronics had strongest CLV (Customer Lifetime Value).
🌍 Region South Zone showed high volume but lower AOV — opportunity for marketing optimization.
💡 9. Business Recommendations

Based on the insights:

1. Loyalty Program for High-Value Customers
Since a small segment contributes majority revenue, targeted offers will boost retention.
2. Personalized Marketing Campaigns
Based on behaviour segments (frequency, spend, region).
3. Promotions in Low-AOV Regions
Incentives or bundles can increase average order value.
4. Stock Optimization for High-Demand Categories
Electronics and Lifestyle categories performed exceptionally well → stocking strategy needed.
5. Increase Marketing Spend in Q2–Q3
Historically the strongest months for revenue.

🔍 10. Folder Structure
customer-behaviour-analysis/
│
├── data/                 # Raw & cleaned datasets
├── notebooks/            # Python EDA
├── sql/                  # MySQL queries
├── dashboard/            # Power BI dashboard (.pbix)
├── images/               # Dashboard screenshots
└── README.md             # Documentation

📦 11. How to Run This Project
▶ Step 1 — Clone Repository
git clone https://github.com/sujalpatel21/Customer-behaviour-analysis
▶ Step 2 — Install Dependencies
pip install -r requirements.txt
▶ Step 3 — Run Notebook
Open Jupyter Notebook:
jupyter notebook
▶ Step 4 — Import SQL File
Use MySQL Workbench or Command Line to run all .sql files.
▶ Step 5 — Open Power BI Dashboard
Open .pbix file from dashboard/ folder. 

🏁 12. Conclusion
This project demonstrates how customer behaviour insights can help businesses:
Increase revenue
Improve customer retention
Optimize product strategy
Target the right customer segments

It showcases full data-analyst capability:
SQL → Python → Visualization → Insights → Business Value.

📬 Contact

Sujal Patel
📍 Ahmedabad, India
📧 sujalpatel6172@gmail.com

🔗 GitHub: https://github.com/sujalpatel21
🔗 LinkedIn: https://linkedin.com/in/sujalpatel21
