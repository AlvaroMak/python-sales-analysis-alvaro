# 📊 Sales & Revenue Analysis with Python  
### End-to-End Data Analysis Project  
**by Álvaro Martínez**

This project demonstrates a complete, business-oriented data analysis workflow using **Python and pandas**, covering the full path from raw transactional data to **actionable insights and an interactive dashboard**.

The focus goes beyond SQL querying, emphasizing **data preparation, validation, aggregation, interpretation, and visualization** aligned with real business questions.

---

## 🚀 Project Overview

In this project, I analyzed sales transaction data to understand **revenue performance over time and across product categories**.

Key steps included:

- Loading and validating multiple sales-related datasets
- Merging transactional and dimensional data into a unified analysis table
- Creating a **revenue metric based on quantity × unit price**
- Analyzing revenue distribution by product category
- Evaluating **monthly revenue trends**
- Exporting a clean dataset for dashboard consumption
- Building an **interactive executive dashboard** for exploration

---

## 🛠️ Key Skills Demonstrated

- Python  
- pandas  
- Data cleaning and transformation  
- Feature engineering (revenue calculation)  
- Exploratory data analysis (EDA)  
- KPI and revenue analysis  
- Data validation and consistency checks  
- Business-oriented communication of insights  
- Dashboarding with Looker Studio  

---

## 📓 Analysis Notebook

The full analysis and data preparation process is documented in the Jupyter Notebook:

📓 **Notebook:**  
`notebooks/sales_analysis.ipynb`

The notebook includes:
- Data loading and validation
- Revenue calculation logic
- Aggregations by category and time
- Visual analysis of trends
- Final dataset export for reporting

---

## 📊 Interactive Dashboard (Looker Studio)

An interactive dashboard was built using **Google Looker Studio**, powered directly by the dataset generated in the Python analysis.

👉 **Dashboard link:**  
https://lookerstudio.google.com/s/ke7ssziwzhY

### Dashboard Features

- **Total Revenue KPI** (updates dynamically based on selected date range)
- **Monthly Revenue Trend**
- **Revenue by Product Category**
- **Global date range filter** affecting all visualizations

### Data Source

The dashboard uses the dataset exported from Python:

```text
/data/sales_dashboard.csv
```

---

## 📂 Repository Structure

```text
/data
  customers.csv
  products.csv
  orders.csv
  order_items.csv
  sales_dashboard.csv

/notebooks
  sales_analysis.ipynb

/src
  data_processing.py

README.md
```

---

## 👤 About Me

I am an Application Support Specialist and SQL Analyst with 13+ years of experience in enterprise environments, currently transitioning into data-focused roles with a strong emphasis on:

- SQL
- Python
- Data analysis
- Business intelligence

I focus on building clear, reliable, and business-driven analytical solutions that bridge technical analysis and decision-making.

🔗 LinkedIn:
https://linkedin.com/in/alvaro-martinez-k
