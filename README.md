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

# 📊 Project Visualizations

## 📈 Monthly Churn Trend

This chart shows how customer churn changed over time, helping identify periods with the highest customer attrition.

![Monthly Churn Trend](images/Monthly%20Churn%20Trend.jpg)

---

## 📊 Churn Rate by Plan Type

This chart compares churn rates across different subscription plans, highlighting which plans are most affected.

![Churn Rate](images/Churn%20Rate.jpg)

---

## 🗺️ Churn Rate by State

This visualization highlights customer churn across different states, helping identify regions with higher churn.

![Churn Rate by Country](images/Churn%20Rate(Country).jpg)

---

## 🔥 Correlation Heatmap

This heatmap illustrates the relationships between key customer churn variables.

- **Churn Score** is strongly positively correlated with **Churn Flag**.
- **Escalations** show a positive relationship with customer churn.
- **Contract Type** has a moderate relationship with churn behavior.
- The heatmap helps identify variables that are most associated with customer churn.

![Correlation Heatmap](images/correlation_heatmap.jpg)
---


## 📁 Project Structure

```
Customer-Churn-Analysis/
│
├── churn_analysis.ipynb
├── customer_churn.db
├── exported_churn_raw_data.csv
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

## 💡Business Insights
 
📈 Customer Churn Rate: 33.94%
💙 Customer Retention Rate: 66.06%
💰 Average Revenue Per User (ARPU): 965.69
⚠️ Revenue at Risk: 72,769.97 due to customer churn

𝗗𝗲𝘁𝗮𝗶𝗹𝗲𝗱 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀:
🔹 Compared churn across Basic, Standard, and Premium plans
🔹 Calculated average customer tenure
🔹 Analyzed complaint and escalation trends
🔹 Studied the relationship between complaints, escalations, and churn using correlation analysis




---

## Business Recommendations

- Investigate the spike in customer churn in Karnataka by analyzing pricing changes, complaint trends, and technical issues.

- Review any pricing or product changes made to the Basic subscription plan, particularly during September, to assess their impact on churn.

- Analyze competitor offerings, as some customers cited switching to competitors as their reason for cancellation.

- Prioritize customers with **High** and **Medium** churn risk by considering their Customer Lifetime Value (CLTV).

- Contact high-value at-risk customers through email, SMS, or phone calls to resolve complaints and improve retention.

- Monitor customer satisfaction (CSAT) and complaint trends regularly to identify potential churn risks early.

 ---


## 🚀 Future Improvements

- Build an interactive Power BI Dashboard
- Develop a churn prediction model using Machine Learning
- Automate the data pipeline
- Deploy the project as an interactive web application

---

## ⭐ If you found this project useful, consider giving it a star!
