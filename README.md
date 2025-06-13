# python-cltv-machine-learning
# **Predicting Customer Lifetime Value (CLTV) with Machine Learning**

## **📄 Overview**

This project demonstrates how to predict **Customer Lifetime Value (CLTV)** using machine learning techniques in Python. The goal is to estimate a customer's future revenue **instantly** — without needing to wait for months of transactional history.

We use a real-world e-commerce dataset, engineer key features like Recency and Frequency, and compare models such as **log-linear regression** and **XGBoost**. The result is a **reusable CLTV prediction function**.

---

## **📁 Dataset**

We use the [Online Retail II dataset](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II) from the UCI Machine Learning Repository.

Due to GitHub file size limits, the dataset is not included here.

📥 You can [download the original Excel file from UCI](https://archive.ics.uci.edu/ml/machine-learning-databases/00502/online_retail_II.xlsx).

---

## **📊 Key Steps in the Notebook**

1. **Data Loading and Exploration**
    
    Load and preview the Online Retail II dataset
    
2. **Data Cleaning**
    
    Filter UK customers, remove missing values and invalid records
    
3. **Feature Engineering (RFM)**
    
    Calculate Recency, Frequency, and Monetary for each customer
    
4. **Initial Regression Model (OLS)**
    
    Predict raw `Monetary` using Recency and Frequency via `statsmodels`
    
5. **Log Transformation & Re-modeling**
    
    Improve model by applying log transformation to the target variable
    
6. **XGBoost Modeling**
    
    Train and evaluate a gradient boosting model for comparison
    
7. **CLTV Prediction Function**
    
    Finalize a reusable function to predict CLTV
    
8. **Model Evaluation & Insights**
    
    Compare model performance using R² and RMSE, explain insights
    
9. **Business Summary**
    
    Highlight how the model helps estimate CLTV instantly without waiting
    

---

## **🔗 Notebook Structure**

**Code, interpretation, and outputs added step by step** for easy understanding.

- Step-by-step modeling
- Evaluation metrics
- Prediction functions
- Business-ready visuals and summary
