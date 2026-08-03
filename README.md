# 🛍️ Customer Shopping Behavior Analysis

**An end-to-end data analytics project** covering data cleaning, exploratory analysis, SQL-based business querying, and interactive dashboarding — built on real-world retail customer data to uncover actionable insights into shopping behavior, customer loyalty, and purchase drivers.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![SQL](https://img.shields.io/badge/SQL-Queries-orange?logo=mysql)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Project Overview

Retail businesses generate huge volumes of customer transaction data, but raw data alone doesn't drive decisions — insight does. This project simulates a real analyst workflow: taking a messy retail dataset all the way from **raw CSV → cleaned data → SQL business queries → Power BI dashboard → final report and presentation**.

The goal was to answer practical business questions such as:
- Which customer segments spend the most, and why?
- How does discounting and promo code usage affect purchase behavior?
- What differentiates loyal, returning, and new customers?
- Which product categories, seasons, and payment methods drive the most revenue?

---

## 🎯 Objectives

- Clean and prepare a raw retail dataset for analysis
- Engineer new features (e.g., age groups, customer loyalty tiers) to enable deeper segmentation
- Load the cleaned data into a SQL database and answer targeted business questions using queries
- Build an interactive Power BI dashboard to visualize customer trends for stakeholders
- Summarize findings into a business report and a stakeholder-ready presentation

---

## 🧰 Tech Stack

| Layer | Tools Used |
|---|---|
| Data Cleaning & EDA | Python (Pandas, NumPy, Matplotlib, Seaborn) — Jupyter Notebook |
| Data Storage & Querying | SQL (MySQL / PostgreSQL / MS SQL Server) |
| Visualization & Dashboarding | Power BI |
| Reporting | PDF report + PowerPoint presentation |

---

## 🗂️ Project Structure

```
customer-trends-data-analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb   # Python: data import, cleaning, EDA, feature engineering
├── customer_behavior_sql_queries.sql           # SQL: business questions answered via queries
├── customer_behavior_dashboard.pbix            # Power BI: interactive dashboard
├── customer_shopping_behavior.csv              # Raw dataset
├── Business Problem Document.pdf               # Problem statement & project scope
├── Customer Shopping Behavior Analysis.pdf     # Final written analysis report
├── Customer-Shopping-Behavior-Analysis.pptx    # Stakeholder presentation deck
├── LICENSE                                     # MIT License
└── README.md                                   # Project documentation (this file)
```

---

## 📊 About the Dataset

The dataset captures customer-level retail transaction records, including fields such as:

`Customer ID`, `Age`, `Gender`, `Item Purchased`, `Category`, `Purchase Amount (USD)`, `Location`, `Size`, `Color`, `Season`, `Review Rating`, `Subscription Status`, `Shipping Type`, `Discount Applied`, `Promo Code Used`, `Previous Purchases`, `Payment Method`, `Frequency of Purchases`.

This gives enough dimensionality to analyze customer demographics, purchasing habits, product preferences, seasonal patterns, and loyalty behavior in combination.

---

## 🔍 Workflow

**1. Data Preparation & EDA (Python)**
- Imported and inspected the raw dataset for nulls, duplicates, and inconsistent formatting
- Cleaned and standardized categorical and numerical fields
- Engineered new features — e.g., **age group buckets** and a **customer loyalty tier** (New / Returning / Loyal, based on previous purchase count)
- Performed univariate and bivariate analysis across purchase amount, category, demographics, and seasonality

**2. Business Analysis (SQL)**
- Loaded the cleaned dataset into a relational database
- Wrote SQL queries to answer real business questions, including:
  - Which age groups and genders spend the most, and on what categories?
  - How do discounts and promo codes influence purchase amount?
  - What is the distribution of customers across loyalty tiers?
  - Which payment methods and shipping types are most preferred?
  - How does purchasing behavior vary by season and location?

**3. Visualization (Power BI)**
- Built an interactive dashboard connecting to the SQL data source
- Designed visuals for customer segmentation, category-wise revenue, seasonal trends, and loyalty distribution
- Enabled filtering by demographic and behavioral attributes for stakeholder exploration

**4. Reporting & Presentation**
- Documented the business problem, methodology, and key findings in a formal report
- Built a presentation summarizing insights and recommendations for a non-technical audience

---

## 💡 Key Insights & Recommendations

> _[ ] Replace this section with your own specific findings — e.g., top-spending age group, category with highest revenue, impact of discounts on order value, loyalty tier breakdown, best-performing season, etc. Numbers here should come directly from your notebook/dashboard output._

---

## 🚀 How to Run This Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/aayus401/customer-trends-data-analysis.git
   cd customer-trends-data-analysis
   ```

2. **Set up the Python environment**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Run the analysis notebook**
   Open `Customer_Shopping_Behavior_Analysis.ipynb` to walk through data import, cleaning, EDA, and feature engineering.

4. **Run the SQL queries**
   - Create a database in MySQL / PostgreSQL / MS SQL Server
   - Load the cleaned data into it
   - Run the queries in `customer_behavior_sql_queries.sql` to answer the business questions

5. **Explore the dashboard**
   Open `customer_behavior_dashboard.pbix` in Power BI Desktop to interact with the visualizations.

6. **Read the report & deck**
   Refer to `Business Problem Document.pdf`, `Customer Shopping Behavior Analysis.pdf`, and `Customer-Shopping-Behavior-Analysis.pptx` for the full write-up and presentation.

---

## 🎓 About This Project

This project was built as a hands-on portfolio piece to demonstrate a complete, end-to-end data analytics skillset — Python, SQL, and Power BI — applied to a realistic retail business problem. It's part of my preparation for **Data Analyst / Data Science placement interviews**.

**[ ] Aayush [Your Full Name]**
🔗 LinkedIn: [Aayush Kumar](https://linkedin.com/in/aayush-kumar-026aa628b)

💻 GitHub: [@aayus401](https://github.com/aayus401)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE) — feel free to explore, fork, or reference it.

---
