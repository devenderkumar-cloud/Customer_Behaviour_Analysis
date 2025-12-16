# Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes **customer shopping behavior** for a retail company using an end-to-end data analytics workflow. The objective is to uncover actionable insights related to customer demographics, purchasing patterns, product performance, discounts, subscriptions, and shipping preferences in order to support data-driven business decisions.

The project integrates **Python, SQL, and Power BI** to demonstrate a complete analytics lifecycle—from raw data to business insights.

---

## 🧠 Business Problem

A retail company observed changing customer purchasing patterns across demographics, product categories, and sales channels. Management wanted to understand:

> *How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize marketing and product strategies?*

---

## 📂 Project Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behavior.csv        # Raw dataset
├── Code.ipynb                            # Python data cleaning & EDA
├── Customer_behavior_SQL_queries.sql     # Business analysis SQL queries
├── customer_behavior_dashboard.pbix      # Power BI dashboard file
├── customer_behavior_dashboard.pdf       # Exported Power BI dashboard
├── Business Problem Document.pdf         # Business context & requirements
└── Project_Report.pdf / .docx            # Final analytical report
```

---

## 🛠 Tools & Technologies

* **Python:** pandas, numpy, SQLAlchemy
* **Database:** PostgreSQL
* **SQL:** Business analysis queries
* **Visualization:** Power BI
* **Environment:** Jupyter Notebook

---

## 🔄 Data Preparation & EDA (Python)

Key steps performed in `Code.ipynb`:

* Loaded and inspected the dataset (3,900 rows × 18 columns)
* Handled missing values in `Review Rating` using **median imputation by category**
* Standardized column names using `snake_case`
* Feature engineering:

  * Created `age_group`
  * Converted purchase frequency into numeric days
* Identified and removed redundant columns (`promo_code_used`)
* Loaded the cleaned dataset into **PostgreSQL** for SQL analysis

---

## 📊 Data Analysis (SQL)

Business questions were answered using structured SQL queries, including:

* Revenue comparison by gender
* Identification of high-spending discount users
* Top-rated and most-purchased products
* Shipping type spending analysis
* Subscriber vs non-subscriber behavior
* Customer segmentation (New, Returning, Loyal)
* Revenue contribution by age group

All queries are available in:

```
Customer_behavior_SQL_queries.sql
```

---

## 📈 Power BI Dashboard

An interactive Power BI dashboard was developed to visualize insights:

### Dashboard Features

* KPI Overview (Total Revenue, Orders, AOV, Review Rating)
* Revenue by Gender and Age Group
* Customer Segmentation & Subscription Analysis
* Shipping Type Performance
* Category-level Drill-Through Dashboard

### Interactivity

* **Slicers used:** Season, Location, Category
* Drill-through functionality for category-level analysis
* Dynamic filtering across all visuals

The dashboard files:

```
customer_behavior_dashboard.pbix
customer_behavior_dashboard.pdf
```

---

## 💡 Key Insights

* Male customers generate a higher share of revenue
* Loyal and returning customers contribute most to total sales
* Subscribers show higher average spending and retention
* Express and free shipping options are associated with higher purchase values
* Middle-aged and young adult customers are the highest revenue contributors

---

## 📌 Business Recommendations

* Promote subscription benefits to increase adoption
* Strengthen loyalty programs for repeat buyers
* Optimize discount strategies to protect margins
* Highlight top-rated and high-performing products
* Use targeted marketing for high-value customer segments

---

## 🚀 Conclusion

This project demonstrates how combining **Python, SQL, and Power BI** enables meaningful customer behavior analysis. The insights generated can help retail businesses enhance customer engagement, improve marketing effectiveness, and drive sustainable growth.

---

## 📎 Author

**Devender Kumar**
Data Analytics Project

---

⭐ If you find this project useful, feel free to star the repository!
