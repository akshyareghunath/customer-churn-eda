# customer-churn-eda

# Customer Churn Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a customer churn dataset to identify key factors influencing customer attrition. The goal is to uncover actionable insights that can help businesses improve customer retention.

---

## 🎯 Objectives
- Understand overall churn behavior
- Identify customer segments with high churn risk
- Analyze the impact of contracts, tenure, pricing, and services on churn
- Provide data-driven business recommendations

---

## 📂 Dataset
- Source: Telco Customer Churn Dataset
- link: https://www.kaggle.com/datasets/blastchar/telco-customer-churn
- Records: ~7,000 customers
- Features include:
  - Customer demographics
  - Contract and billing information
  - Service usage details
  - Churn indicator (Yes/No)

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 🔍 Key Analysis Performed

### 1️⃣ Churn Distribution
- Around **26–27% of customers churned**, indicating a moderate imbalance.

### 2️⃣ Contract Type vs Churn
- **Month-to-month contracts show the highest churn**
- Long-term contracts significantly reduce churn

### 3️⃣ Tenure vs Churn
- Customers in their **first year are most likely to churn**
- Churn decreases steadily with increasing tenure

### 4️⃣ Monthly Charges vs Churn
- Churned customers tend to have **higher monthly charges**
- Box plot analysis shows pricing is a key churn driver

### 5️⃣ Services vs Churn
- Customers without **Onlinestreamingmovies and Onlinestreaingtv** show higher churn
- **Fiber optic internet users** have higher churn compared to other types

---

## 📊 Visualizations
- Bar charts for churn percentage comparisons
- Box plots to analyze pricing distributions
- Grouped analysis using tenure and service categories

---

## 🧠 Business Insights
- Early-stage customers need stronger onboarding and engagement
- Incentives should be offered to move customers to long-term contracts
- High-priced plans should improve value perception
- Support services play a crucial role in customer retention

---

## 📁 Repository Structure
