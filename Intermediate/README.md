# 🏦 Loan Approval Prediction – (Intermediate Task)

This project implements a Machine Learning-based classification system that predicts whether a loan application should be approved based on applicant data like income, credit history, education, and employment. This task is part of the **ShadowFox AIML Internship (Intermediate Level)**.

---

## 📌 Problem Statement

> Predict loan approvals using historical applicant data by building and evaluating a machine learning model. The goal is to help fintech and banking institutions make informed, automated lending decisions.

---

## 📁 Dataset Overview

The dataset contains features such as:

- Applicant & Coapplicant Income
- Education
- Marital Status
- Employment Type
- Loan Amount & Loan Term
- Credit History
- Property Area
- Loan Status (Target)

---

## 🔍 ML Pipeline

### ✅ Data Preprocessing
- Missing values handled using mode/median
- One-hot encoding for categorical variables
- Outlier removal using IQR (optional)
- Feature scaling using `StandardScaler`

### ✅ Models Trained
- **Random Forest Classifier**
- **Support Vector Classifier (SVC)**

---

## 📊 Evaluation Results

### 🔸 Random Forest Classifier
- Accuracy: **83.48%**
- False Negatives: **3**
- False Positives: **16**

### 🔸 SVC Classifier
- Accuracy: **83.48%**
- False Negatives: **1**
- False Positives: **18**

📌 **Trade-off**:  
SVC was more conservative (less likely to miss eligible applicants), while Random Forest had a slightly better balance between FP and FN.

---

## 🛠️ Tech Stack

- Python (Jupyter Notebook)
- Pandas, NumPy
- scikit-learn
- Seaborn, Plotly (EDA & visualization)
- StandardScaler, get_dummies

---

## ✅ Completed Steps

✔️ Data Preprocessing  
✔️ Feature Engineering  
✔️ Model Training (RandomForest, SVC)  
✔️ Performance Evaluation (Accuracy, Confusion Matrix)  
✔️ Business Interpretation of Results  

---

## 🙌 Author

**Dhanush G M**  
AIML Intern @ ShadowFox  
[GitHub](https://github.com/dgm003/ShadowFox) | [LinkedIn](www.linkedin.com/in/dhanush-gm)

---

