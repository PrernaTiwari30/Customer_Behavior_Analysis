# 📊 Customer Behavior Analysis Project

## 📌 Overview

This project demonstrates an **end-to-end data analytics workflow**, starting from raw data ingestion to actionable business insights.
The project covers **data loading, exploratory data analysis (EDA), data cleaning, SQL-based analysis using PostgreSQL, and interactive dashboard creation using Power BI**.

The goal is to analyze customer behavior and purchasing patterns to support data-driven decision-making.

---

## 📂 Dataset

* The dataset contains **customer-level transaction data**
* Key attributes include:

  * Customer demographics (age, gender)
  * Product and category information
  * Purchase amount
  * Discounts applied
  * Shipping type
  * Subscription status
  * Review ratings
  * Previous purchase history

> The dataset is loaded and processed using Python before being stored in PostgreSQL for further analysis.

---

## 🛠️ Tools & Technologies

* **Python** 
* **PostgreSQL** (SQL queries, window functions, aggregations)
* **Power BI** (Data visualization & dashboards)
* **SQLAlchemy & psycopg2** (Python–PostgreSQL connection)
* **pgAdmin** (Database management)

---

## 🔄 Project Workflow / Steps

### 1️⃣ Data Loading (Python)

* Load the raw dataset into Python using Pandas
* Inspect schema, data types, and basic structure

### 2️⃣ Exploratory Data Analysis (EDA)

* Analyze distributions and trends
* Identify missing values and outliers
* Understand customer purchasing behavior

### 3️⃣ Data Cleaning & Preparation

* Handle missing and inconsistent values
* Standardize categorical variables
* Convert data types for SQL compatibility

### 4️⃣ Load Data into PostgreSQL

* Create database and tables
* Load cleaned data into PostgreSQL using Pandas `to_sql()`

### 5️⃣ SQL Analysis (PostgreSQL)

* Write SQL queries to answer key business questions, such as:

  * Revenue by gender and age group
  * Subscription vs non-subscription spending
  * Top products and categories
  * Discount usage analysis
* Use **GROUP BY, JOINs, CTEs, and window functions**

### 6️⃣ Power BI Dashboard

* Connect Power BI to PostgreSQL
* Build interactive dashboards
* Visualize trends and customer segments using slicers

---

## 📈 Power BI Dashboard

The Power BI dashboard includes:

* Total no. of customers and average purchase amount
* Revenue breakdown by gender and age group
* Top-performing products and categories
* Subscription vs non-subscription comparison
* Average Review Rating

The dashboard enables **interactive filtering** and provides clear insights for stakeholders.

---

## 📊 Results & Insights

* Identified key customer segments contributing the most revenue
* Found differences in spending behavior between subscribed and non-subscribed customers
* Highlighted top products and categories driving sales
* Analyzed the impact of discounts on purchasing behavior

These insights can help improve **marketing strategy, pricing decisions, and customer retention**.

---

## ▶️ How to Run This Project

### Prerequisites

* Python 3.x
* PostgreSQL installed and running
* Power BI Desktop
* Required Python libraries:

```bash
pip install pandas sqlalchemy psycopg2-binary
```

### Steps

1. Load and clean data using the Python scripts
2. Update PostgreSQL connection details in the code
3. Load data into PostgreSQL
4. Run SQL queries for analysis
5. Open Power BI and connect to the PostgreSQL database
6. Refresh the dashboard to view insights
   
