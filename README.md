# Customer-Churn-Prediction
# Customer Churn Prediction using Machine Learning  

## Overview  
This project focuses on predicting **customer churn** using **Machine Learning** techniques. By analyzing customer demographics, transaction history, and engagement levels, we build predictive models to identify customers at risk of leaving. The project follows a structured workflow, including **data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation**.  

---

## Methodology  

### 1. Data Preprocessing  
- **Handling Missing Values:** Imputed missing data using statistical methods.  
- **Encoding Categorical Variables:** Converted categorical features into numerical format using **One-Hot Encoding** and **Label Encoding**.  
- **Feature Scaling:** Used **StandardScaler/MinMaxScaler** for normalization.    

### 2. Exploratory Data Analysis (EDA)  
- **Churn Rate Analysis:** Examined the percentage of customers who churned.  
- **Correlation Analysis:** Identified key factors influencing churn.  
- **Data Visualization:** Used **Seaborn & Matplotlib** for insights on customer behavior.  

### 3. Feature Engineering  
- **Created new features** like customer tenure, engagement score, transaction frequency, and revenue contribution.  
- **Removed redundant & highly correlated features** for better model performance.  

### 4. Model Training & Evaluation  
- **Algorithms Used:**  
  - KNN
  - Random Forest  
- **Performance Metrics:**  
  - **Accuracy, Precision, Recall, F1-Score**.   
