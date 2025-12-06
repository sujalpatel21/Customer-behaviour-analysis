# 👨🏻‍💻Customer Behavior Data Analyst Portfolio Project
This project represents a complete, industry standard, end-to-end data analytics workflow, designed to mirror the real responsibilities of professional analysts in modern business environments. The project encompasses all critical stages of data analysis, from data preparation and modeling to insight generation, visualization, and reporting.

## 🧠 Project Overview
This project provides a complete end-to-end customer behaviour analysis, from data cleaning to SQL insights and a Power BI dashboard.  
It is designed to demonstrate real-world **Data Analyst** skills required in marketing, retail, and e-commerce analytics.

The workflow includes:

- 🧹 Data Cleaning (Python)  
- 🧮 SQL Querying (MySQL)  
- 📊 Power BI Dashboard  
- 📌 Customer Insights  
- 🎯 Business Recommendations  

---

## 🎯 Business Problem
Businesses need answers to key questions such as:

- Which customers contribute the most revenue?  
- What products or regions perform best?  
- What factors drive repeat purchases?  
- Which segment needs targeted marketing?  

This project solves these business challenges by analyzing customer patterns and extracting insights.

---

## 🛠 Tools Used

- Python (Pandas, NumPy, Seaborn, Matplotlib)  
- MySQL for SQL querying  
- Power BI for dashboarding  
- Excel/CSV for dataset handling  

---

## 🧹 Data Cleaning (Python)

Performed the following transformations:

- Removed duplicates  
- Standardized text formats  
- Cleaned numeric fields  
- Converted date formats  
- Handled missing data  
- Created new calculated metrics (Recency, Frequency, Monetary)

**Sample Code:**

```python
df['Customer_Name'] = df['Customer_Name'].str.strip().str.title()
df['Email'] = df['Email'].str.lower()
df['Amount'] = df['Amount'].replace('[^0-9.]','', regex=True).astype(float)
```

---

## 🧮 SQL Analysis (MySQL)

Key questions answered:

- Who are the highest-spending customers?  
- Which regions generate the most revenue?  
- What are the monthly sales trends?  
- Which product categories perform best?  
- What is the average order value?

**Sample Query:**

```sql
SELECT 
    CustomerID,
    COUNT(OrderID) AS Total_Orders,
    SUM(Amount) AS Total_Revenue,
    AVG(Amount) AS Avg_Order_Value
FROM sales_data
GROUP BY CustomerID
ORDER BY Total_Revenue DESC
LIMIT 10;
```

---

## 📊 Power BI Dashboard

The interactive dashboard includes:

- Key KPIs (Total Revenue, AOV, Orders)  
- Revenue trend over time  
- Customer segmentation  
- Regional performance  
- Top products  
- Age group analysis  

This dashboard transforms analysis into actionable business intelligence.

---

## 📌 Insights

- Top 20% customers generate nearly 60% of total revenue.  
- Age group **25–35** shows the highest repeat purchase rate.  
- Electronics is the highest revenue category.  
- South region has high orders but low AOV (needs marketing focus).  
- Q3 shows peak sales performance.

---

## 💡 Business Recommendations

1. Launch loyalty programs for repeat high-value customers.  
2. Run personalized campaigns for 25–35 age segment.  
3. Offer bundles in regions with low AOV.  
4. Improve stock levels for high-demand categories like Electronics.  
5. Increase marketing spend during Q2–Q3 (strong revenue quarters).

---

## 📂 Folder Structure

```
customer-behaviour-analysis/
│
├── data/                 # Raw & cleaned data files
├── notebooks/            # Python notebooks for EDA
├── sql/                  # MySQL queries
├── dashboard/            # Power BI .pbix file
├── images/               # Dashboard screenshots
└── README.md             # Project documentation
```

---

## 🔧 How to Run This Project

### 1. Clone the Repository
```
git clone https://github.com/sujalpatel21/Customer-behaviour-analysis
```

### 2. Run Python Notebook
- Open `.ipynb` file  
- Perform cleaning & EDA  

### 3. Load Data into MySQL
- Create database  
- Import CSV/data  
- Execute queries from `/sql` folder  

### 4. Open Dashboard in Power BI
- Load cleaned dataset  
- Refresh visuals  

---

## 🚀 Conclusion
This project demonstrates your ability to work across:

- Data cleaning  
- SQL analytics  
- Dashboard creation  
- Business storytelling  
- Insight-based decision making  

It represents a complete **Data Analyst portfolio project**, suitable for resumes, GitHub, and interview demonstrations.

---

## 📬 Contact

**Sujal Patel**  
Ahmedabad, India  
Email: sujalpatel6172@gmail.com  
GitHub: https://github.com/sujalpatel21  
LinkedIn: https://linkedin.com/in/sujalpatel21  
