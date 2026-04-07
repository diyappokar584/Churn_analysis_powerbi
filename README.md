# Churn_analysis_powerbi
End-to-end Customer Churn Analysis using PostgreSQL, Power BI, and Python. Includes ETL, data cleaning, visualization, and Random Forest model to predict churn, analyze customer behavior, and generate actionable insights for retention strategies.

# 📊 Customer Churn Analysis (PostgreSQL + Power BI + Python)

## 📌 Project Overview
Customer churn analysis is essential for understanding why customers leave and how to retain them. This project builds a complete data pipeline and machine learning model to analyze and predict customer churn.
The project covers ETL, data cleaning, visualization, and predictive modeling to generate actionable business insights.

---

## 🎯 Project Objectives
- Analyze customer data across multiple dimensions:
  - Demographics
  - Geography
  - Account & Payment Information
  - Services Used
- Identify churn patterns and customer behavior
- Build a machine learning model to predict future churners
- Visualize insights and predictions using Power BI

---

## 🛠️ Tech Stack
- **Database:** PostgreSQL
- **Visualization:** Power BI
- **Programming:** Python (Pandas, NumPy, Matplotlib, Seaborn)
- **Machine Learning:** Random Forest (Scikit-learn)

---

## ⚙️ Project Workflow

### 1. ETL & Data Cleaning (PostgreSQL)
- Imported CSV data into staging table
- Performed data exploration (null checks, distributions)
- Cleaned missing values using SQL
- Created production table for analysis

### 2. Data Transformation (Power BI)
- Created calculated columns:
  - Churn Status (0/1)
  - Monthly Charge Range
- Built mapping tables:
  - Age Groups
  - Tenure Groups
- Performed data modeling and relationships

### 3. Data Visualization (Power BI)
Developed interactive dashboards with:
- Total Customers, Churn Rate, New Joiners
- Demographic analysis (Age, Gender)
- Account insights (Contract, Payment Method)
- Geographic trends (State-wise churn)
- Service usage impact on churn

---

## 🤖 Machine Learning Model
- Algorithm: **Random Forest Classifier**
- Data preprocessing:
  - Label encoding for categorical variables
  - Train-test split (80/20)
- Model evaluation:
  - Confusion Matrix
  - Classification Report
- Feature importance analysis

---

## 🔮 Churn Prediction
- Predicted churn for new customers
- Filtered high-risk customers
- Exported results for visualization

---

## 📊 Key Insights
- Customers with higher monthly charges show higher churn rates
- Contract type significantly affects retention
- Short tenure customers are more likely to churn
- Certain services influence churn behavior

---

## Dashboard Images
-Check Churn_analysis_ss.pdf

---
