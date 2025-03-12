# 💰 Loan Application Approval Prediction

## 📌 Overview
This project focuses on **predicting loan application approval** using **machine learning models**. The goal is to build a robust classification model that determines whether a loan application should be **accepted** or **rejected** based on customer details.

## 🎯 Objective
- **Develop a classification model** for loan approval prediction.
- **Perform data cleaning & preprocessing** to handle missing values and categorical encoding.
- **Explore the dataset using EDA** to understand patterns and correlations.
- **Train & compare multiple machine learning models**.
- **Evaluate models using classification metrics**.
- **Explain model decisions** using SHAP values or feature importance.

---

## 📊 Dataset
### **📌 Data Source**
📂 Dataset Link: [Loan Dataset on Kaggle](https://www.kaggle.com/datasets/abhishek14398/loan-dataset/data)

### **📌 Dataset Description**
The dataset contains customer information used for **loan decisions (approval/rejection)**. Key features include:
- **Income** 💰
- **Credit History** 🏦
- **Employment Type** 👨‍💼
- **Loan Amount** 📄
- **Other financial & demographic attributes** 📊

---

## 🏗️ Methodology
### **📌 Data Understanding & Cleaning**
✔ Check for **missing values, inconsistencies, and outliers**.  
✔ Handle **missing values** using imputation techniques.  
✔ **Encode categorical variables** (One-Hot Encoding, Label Encoding).  
✔ **Scale numerical features** for model optimization.  

### **📌 Exploratory Data Analysis (EDA)**
✔ Visualize **correlations** between features and loan decisions.  
✔ Analyze **class distribution** (Accepted vs. Rejected loans).  
✔ Identify **important factors affecting loan approval**.  

### **📌 Model Development**
We train and compare **at least 3 classification models**:
✔ **Logistic Regression**  
✔ **Decision Trees / Random Forest**  
✔ **Gradient Boosting (XGBoost, LightGBM, CatBoost)**  

🔹 **Hyperparameter tuning** using GridSearchCV / RandomizedSearchCV.  
🔹 **Feature selection** to improve model performance.  

### **📌 Model Evaluation**
✔ Metrics used:
   - **Accuracy**
   - **Precision & Recall**
   - **F1 Score**
   - **AUC-ROC Curve**  
✔ Compare models & select the best-performing one.  

### **📌 Model Explainability**
✔ Use **SHAP values** or **Feature Importance** to explain predictions.  
✔ Identify the **most important factors** in loan approval decisions.  

### **📌 Deployment Simulation **
✔ Run a **script Deployment** to use the app and get a **loan approval prediction**.  

---
