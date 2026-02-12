# 🏦 CreditWise Loan Approval System

An end-to-end Supervised Machine Learning project that predicts whether a loan application will be approved based on applicant details.

---

## 📌 Project Overview

The CreditWise Loan Approval System is a Binary Classification project built to simulate how financial institutions evaluate loan applications.

This project demonstrates a complete Machine Learning pipeline including:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training
- Model Evaluation
- Model Comparison

---

## 🎯 Objective

To build a predictive model that determines whether a loan application will be:

- ✅ Approved  
- ❌ Not Approved  

based on applicant financial and demographic information.

---

## 📊 Dataset Description

The dataset consists of applicant-level features such as:

- Applicant Income  
- Coapplicant Income  
- Employment Status  
- Marital Status  
- Education Level  
- Credit Score  
- Loan Amount  
- Property Area  
- Existing Loans  
- Loan Purpose  

### 🎯 Target Variable:
`Loan_Approved (Yes / No)`

---

## 🔎 Exploratory Data Analysis (EDA)

Performed detailed analysis including:

- Checking for missing values
- Studying class distribution
- Visualizing feature impact on loan approval
- Correlation analysis for numerical features

EDA helped in understanding patterns and improving model performance.

---

## ⚙️ Feature Engineering & Preprocessing

The following preprocessing steps were applied:

- Label Encoding for binary categorical features
- One-Hot Encoding for multi-category variables
- Feature Scaling using StandardScaler
- Proper train-test split to avoid data leakage

Care was taken to ensure preprocessing consistency for reliable model evaluation.

---

## 🤖 Models Implemented

Three supervised learning algorithms were implemented and compared:

1. **K-Nearest Neighbors (KNN)**
2. **Logistic Regression**
3. **Naive Bayes**

---

## 📈 Model Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

These metrics provided a balanced understanding of model performance.

---

## 🏆 Best Performing Model

Logistic Regression achieved the most balanced performance with:

- Highest Accuracy
- Strong Precision and Recall balance
- Highest F1 Score

This indicates that the dataset is reasonably linearly separable and benefits from feature scaling.

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📚 Key Learnings

- Understanding of complete ML workflow
- Importance of correct preprocessing techniques
- Handling categorical data effectively
- Model comparison using multiple evaluation metrics
- Debugging preprocessing and encoding errors

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation for robust evaluation
- Handling class imbalance techniques
- Deployment using Streamlit or Flask
- Building a simple web-based prediction interface

---

## 👩‍💻 Author

**Vaishnavi Rathi**  

---

⭐ If you found this project interesting, feel free to explore and connect!
