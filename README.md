# 📊 Telecom Customer Retention Analysis

## 📌 Project Overview
This project analyzes customer churn in the telecom industry using a unique dataset. The goal is to identify key factors affecting churn and provide insights to improve customer retention.

## 📂 Dataset Description
- **Total Records:** 1,000 customers
- **Features:** Customer demographics, tenure, billing, contract type, and churn status
- **Target Variable:** `Churn` (Yes/No)

## 🛠 Data Cleaning & Preprocessing
- No **missing values** or **duplicates** were found.
- The dataset was structured correctly for analysis.
- Converted categorical variables for better analysis.

## 🔍 Exploratory Data Analysis (EDA)

### 📊 1️⃣ Churn Distribution
- **Churn Rate:** 32% (320 customers churned out of 1,000).
- **Retention Rate:** 68% of customers stayed.

### 📜 2️⃣ Contract Type & Churn
- **Month-to-month contracts** have the highest churn (**48% of customers**).
- **Long-term contracts (1-year, 2-year)** show significantly lower churn rates.

### 🌐 3️⃣ Internet Service Impact
- **Fiber optic users** have the highest churn rate.
- **DSL users** churn less compared to fiber optic.
- **No internet service customers** have the lowest churn.

### ⏳ 4️⃣ Tenure & Churn
- Customers with **shorter tenure (<12 months)** are more likely to churn.
- Long-tenure customers are more loyal.

### 💳 5️⃣ Payment Methods & Churn
- Customers paying via **electronic check** have the highest churn rate.
- **Bank transfers and credit cards** show lower churn rates.

### 💰 6️⃣ Monthly Charges & Churn
- Higher **monthly charges** correlate with higher churn rates.
- Customers paying **above $80 per month** are more likely to churn.

## 🔥 Key Business Insights
- Encourage **long-term contracts** to reduce churn.
- Offer **discounts to high-monthly charge customers** to retain them.
- Improve **customer experience for fiber optic users** to lower churn.
- Target **electronic check users** with retention campaigns.
- Provide **better onboarding for new customers** to increase tenure.
- Introduce **personalized offers for high-risk churn customers**.

## 🚀 Next Steps
- Build a **Churn Prediction Model (Optional).**
- Visualize insights using **Tableau/Power BI.**
- Develop **customer engagement strategies** based on insights.

## 🖥 How to Run This Project
1. Load the dataset in Python using Pandas.
2. Perform EDA with Matplotlib/Seaborn.
3. Visualize insights using Power BI/Tableau.



