# 📊 Customer Churn Analysis & Customer Intelligence

An end-to-end Data Analytics project that analyzes customer churn using Python, SQL, and data visualization techniques. The project focuses on identifying churn patterns, customer behavior, revenue impact, and business insights through data cleaning, feature engineering, exploratory data analysis (EDA), and visualization.

---

## 📌 Project Overview

Customer churn is one of the most important business metrics for subscription-based companies. This project combines customer, subscription, and support data from a SQLite database to uncover the key factors influencing customer churn and provide actionable business insights.

---

## 🎯 Project Objectives

- Import data from a relational SQLite database
- Clean and preprocess raw data
- Merge multiple tables into a single analytical dataset
- Perform Feature Engineering
- Analyze customer churn and retention
- Create business KPIs
- Visualize customer behavior and churn trends

---

## 🛠️ Tech Stack

- Python
- SQL (SQLite)
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

The project uses three relational tables:

- 👤 Customer Data
- 💳 Subscription Data
- 🎧 Support Data

These tables are joined together to create a complete customer-level dataset.

---

## ⚙️ Project Workflow

### 1. Data Import
- Import data from SQLite database
- Load each table into Pandas DataFrames

### 2. Data Cleaning
- Rename columns
- Remove unnecessary columns
- Convert data types
- Standardize categorical values
- Handle missing values

### 3. Feature Engineering
- Create Churn Flag
- Calculate Customer Tenure
- Calculate Complaint Count
- Create Churn Risk categories
- Merge customer, subscription, and support datasets

### 4. Exploratory Data Analysis (EDA)
- Churn Rate
- Retention Rate
- Average Revenue Per User (ARPU)
- Revenue at Risk
- Average Customer Tenure
- Churn by Plan Type
- Complaint Analysis
- Escalation vs Churn Correlation

### 5. Data Visualization
- Monthly Churn Trend
- Churn by Plan Type
- Churn by State
- Correlation Heatmap
- Pair Plot
- Categorical Plot (Catplot)
- Pivot Tables

---

## 📊 Key KPIs

- Churn Rate
- Retention Rate
- ARPU
- Revenue at Risk
- Escalation Rate
- Average Complaints
- Customer Tenure
- Churn Risk
- Correlation

---

## 📈 Visualizations

- Line Chart
- Bar Chart
- Correlation Heatmap
- Pair Plot
- Catplot
- Pivot Tables

---

## 📁 Project Structure

```
Customer-Churn-Analysis/
│
├── churn_analysis.ipynb
├── customer_churn.db
├── exported_churn_data.csv
├── README.md
```

---

## 💼 Skills Demonstrated

- SQL
- Python
- Pandas
- NumPy
- Data Cleaning
- Data Wrangling
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Business Intelligence
- Data Visualization
- Matplotlib
- Seaborn
- SQLite

---

## 📌 Business Insights

- Identified customer churn patterns across subscription plans.
- Measured customer retention and revenue impact.
- Analyzed customer complaints and escalation behavior.
- Evaluated customer tenure and churn risk.
- Built visual dashboards to support data-driven decision-making.

---

## 🚀 Future Improvements

- Build an interactive Power BI Dashboard
- Develop a churn prediction model using Machine Learning
- Automate the data pipeline
- Deploy the project as an interactive web application

---

## ⭐ If you found this project useful, consider giving it a star!
