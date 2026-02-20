# 📊 Telco Customer Churn Prediction

## 📌 Project Overview


    This project aims to predict whether a customer will churn or not using machine learning models including 
    Logistic Regression, Random Forest, and XGBoost. 
    SHAP was used for model interpretability.

    
## 🎯 Project Objective


    Predict whether a customer will churn (1) or remain retained (0) to help telecom companies reduce revenue loss through early intervention.

    
## 📂 Dataset


* 7043 customer records
* 24 features
* Target Variable: Churn
* 1 → Churned
* 0 → Retained

    
## 🔎 Steps Performed


* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Training:
* Logistic Regression
* Random Forest
* XGBoost
  Model Evaluation using:
   * ROC-AUC
   * Precision
   * Recall
   * F1-score
Model Explainability using SHAP

    
## 📈 Model Evaluation


    Although Random Forest achieved a slightly higher ROC-AUC score, 
    the primary objective of this project is to correctly classify customers who are likely to churn.
    Since missing a churner (False Negative) results in greater business loss than incorrectly predicting a retained customer as churn (False Positive), 
    Recall becomes the more critical metric.
    Logistic Regression achieved higher Recall and F1-score, making it better aligned with business objectives. 
    Therefore, Logistic Regression was selected as the final model.

    
## 🔍 Key Insights


* Month-to-month contracts have higher churn rates
* Customers with lower tenure are more likely to churn
* Higher monthly charges increase churn probability

    
## 🛠 Tools & Libraries


* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* SHAP
* Matplotlib / Seaborn



