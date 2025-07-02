# 📉 Customer Churn Analysis - EDA Project

This project is an Exploratory Data Analysis (EDA) of a telecom company’s customer data to identify patterns and key factors leading to **customer churn**. The goal is to gain business insights that can help reduce churn rates and improve customer retention.

## 📂 Dataset Description

The dataset contains information about **7,043 customers** including:

- Demographics (Gender, Senior Citizen, Dependents)
- Services (Internet, Phone, Tech Support, Streaming)
- Account Info (Contract Type, Payment Method, Tenure)
- Target: `Churn` (Yes/No)

## 🛠 Tools & Libraries Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Key Visualizations & Insights

1. **Churn Distribution**  
   - ~26% customers have churned (pie chart).

2. **Churn by Gender**  
   - Gender has minimal influence on churn.

3. **Tenure Distribution**  
   - New customers (low tenure) are more likely to churn.

4. **Contract Type vs Churn**  
   - Customers with **month-to-month contracts** churn the most.

5. **Internet Service**  
   - **Fiber optic** users churn more than DSL users.

6. **Payment Method Analysis**  
   - Customers using **electronic checks** are more likely to churn.

7. **Total & Monthly Charges**  
   - Higher monthly charges increase churn risk.
