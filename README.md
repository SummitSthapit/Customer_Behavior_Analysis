# Customer Behavior Analysis

A data analytics project that analyzes customer shopping behavior using **SQL**, **Python (Pandas)**, and **Power BI** to uncover purchasing patterns, customer demographics, and business insights.

The dataset was taken from https://www.kaggle.com/datasets/wardabilal/customer-shopping-behaviour-analysis.

---

## Project Overview

Understanding customer behavior is essential for making data-driven business decisions. This project demonstrates an end-to-end analytics workflow, from data cleaning and exploration to SQL querying and interactive dashboard creation.

The project answers business questions such as:

- Which customer groups spend the most?
- How do age and gender influence purchasing behavior?
- Which product categories generate the highest sales?
- What payment methods are most commonly used?
- How do seasonal trends affect shopping patterns?

---

## Tech Stack

- **Python**
  - Pandas
  - SQLAlchemy
-**PostgreSQL**  
- **SQL**
- **Power BI**
- **Jupyter Notebook**

---

## Project Workflow

### 1. Data Cleaning (Python)

- Loaded the dataset using Pandas
- Handled missing values
- Removed duplicate records
- Standardized column names
- Performed data preprocessing
- Connected to the SQL database
- Exported the DF to the database

---

### 2. Data Analysis (SQL)

Used SQL to answer business questions, including:

- Customer demographics
- Average purchase amount
- Sales by category
- Shopping frequency
- Payment method analysis
- Seasonal purchasing trends

---

### 3. Dashboard Development (Power BI)

Connected Power BI directly to the SQL database to build an interactive dashboard featuring:

- Sales overview
- Customer demographics
- Product category analysis
- Seasonal trends
- Payment method distribution
- Shopping frequency
- Interactive filters and slicers

---

## Repository Structure

```
Customer_Behavior_Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── notebooks/
│   └── Customer_Behavior_Analysis.ipynb
│
├── sql/
│   └── customer_behavior_queries.sql
│
├── powerbi/
│   └── Customer_Behavior_Dashboard.pbix
│
├── images/
│   └── dashboard.png
│
└── README.m
```
---

## Key Insights

Some insights obtained from the analysis include:

- High-income customers tend to have higher purchase values.
- Clothing and Electronics are among the top-performing product categories.
- Certain payment methods are preferred by specific customer groups.
- Shopping behavior varies across different seasons.
- Customer demographics have a noticeable impact on spending patterns.

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- SQL Query Writing
- Data Visualization
- Dashboard Design
- Business Intelligence
- Data Storytelling

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Python | Data Cleaning & Analysis |
| Pandas | Data Manipulation |
| SQL | Data Querying |
| Power BI | Dashboard & Visualization |
| Jupyter Notebook | Analysis Environment |

---

## Future Improvements

- Add predictive analytics using machine learning
- Deploy the dashboard online
