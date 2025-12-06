📊 --Project Overview

This project analyses customer behaviour, identifies trends, segments customers, and uncovers insights that help businesses improve sales, marketing, and retention.

The workflow includes:

🧹 Data Cleaning (Python)

🧮 SQL Analysis (MySQL)

📊 Dashboarding (Power BI)

📌 Insights & Business Recommendations

📈 KPIs and Trends Analysis

This is an ideal project for Data Analyst roles across retail, marketing, and e-commerce domains.


🧠 Business Problem


Most businesses collect customer data but cannot answer critical questions:

Which customers contribute most to revenue?

What product categories perform best?

Which regions underperform and why?

Which age group or segment buys the most?

What factors drive repeat purchases?

This project solves these business challenges through structured analytics.


🛠 Tools Used


🐍 Python – Data cleaning & EDA

🗄️ MySQL – Querying & business insights

📊 Power BI – Dashboard & storytelling

📁 Excel/CSV – Raw dataset handling

🧹 Pandas, NumPy, Seaborn, Matplotlib

🧹 Data Cleaning (Python)

Tasks performed:


Removed duplicates

Standardized text formats (email, names)

Cleaned numeric fields

Converted dates

Handled missing values

Created new columns like Total_Spend, Recency, Frequency


🧮 SQL Analysis (MySQL)


Key business questions answered:

Who are the top 10 highest-spending customers?

What is the average order value across segments?

Which regions generate the highest revenue?

What category sells the most?

What are monthly sales trends?

Example Query:

SELECT 
    CustomerID,
    COUNT(OrderID) AS Total_Orders,
    SUM(Amount) AS Total_Revenue,
    AVG(Amount) AS Avg_Order_Value
FROM sales_data
GROUP BY CustomerID
ORDER BY Total_Revenue DESC
LIMIT 10;


📊 Dashboard (Power BI)


Dashboard Includes:

📈 Revenue Trends

📌 Customer Segmentation

🛒 Product Category Performance

🌍 Regional Analysis

🧍 Age Group Analysis

💰 Top Customers by Revenue

Key KPIs (Total Revenue, Avg Order Value, Total Orders)

This makes insights easy to understand for business stakeholders.


📌 Insights


Major insights from the analysis:

20% of customers contributed ~60% of total revenue.

Age group 25–35 shows the highest repeat purchases.

Electronics is the highest revenue-generating product category.

The South region has high volume but low AOV (needs marketing optimization).

Q3 is the strongest quarter for revenue growth.


🎯 Business Recommendations


Based on insights:

1️⃣ Launch a loyalty program for top customers

These customers drive most revenue and are easier to retain.

2️⃣ Improve marketing focus in low-performing regions

Bundle offers and discounts can increase AOV.

3️⃣ Target age group 25–35 with tailored campaigns

They have the highest repeat purchase rate.

4️⃣ Improve stock availability for high-demand categories

Especially electronics and fashion.

5️⃣ Increase marketing spend during Q2–Q3

Peak revenue periods.


📂 Folder Structure
customer-behaviour-analysis/
│
├── data/                 # Raw & cleaned datasets
├── notebooks/            # Python notebooks
├── sql/                  # MySQL queries
├── dashboard/            # Power BI .pbix file
├── images/               # Dashboard screenshots
└── README.md             # Project documentation

🔧 How to Run This Project
1. Clone the Repository
git clone https://github.com/sujalpatel21/Customer-behaviour-analysis

2. Open Python Notebook

Run data cleaning & EDA

Export cleaned dataset

3. Load Data into MySQL

Create a database

Import the cleaned dataset

Run queries from /sql folder

4. Open Power BI Dashboard

Load SQL or CSV

Refresh visuals

🚀 Conclusion

This project demonstrates your ability to:

Clean real-world data

Run SQL queries for business insights

Build professional dashboards

Convert analysis into business recommendations

It showcases complete data analytics workflow, making it ideal for Data Analyst job applications.

📬 Contact

Sujal Patel
📍 Ahmedabad, India
📧 sujalpatel6172@gmail.com

🔗 GitHub: https://github.com/sujalpatel21

🔗 LinkedIn: https://linkedin.com/in/sujalpatel21
