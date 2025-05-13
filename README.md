# Loan Eligibility Prediction

This project aims to predict whether a loan applicant is eligible for loan approval based on financial and personal information, using a Logistic Regression model.

## 📌 Overview
- Dataset with over 1.3 million rows and 151 columns
- Dataset Link: https://www.kaggle.com/datasets/wordsforthewise/lending-club/data
- Preprocessing techniques including:
  - Handling missing values
  - Cleaning and converting categorical features 
  - One-hot encoding for categorical variables
- Logistic Regression model
- Threshold tuning and performance comparison

## 📊 Technologies and Libraries Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 🚀 How to Run

1. Install the dependencies:
```bash
pip install -r requirements.txt
```

2. Open the notebook:
```bash
jupyter notebook notebook/Loan_Eligibility_Prediction.ipynb
```

## 🛠️ Preprocessing Highlights
- Cleaned `emp_length` column to retain only number
- Applied one-hot encoding on categorical features
- Handled missing values using mean or mode where appropriate
- Oversampling using SMOTE

## 📈 Model
- Trained Logistic Regression using cleaned and encoded dataset
- Evaluated performance with accuracy and classification report
- Adjusted threshold (e.g., 0.4) to optimize prediction sensitivity

## ✍️ Author
Vũ Hoàng Huy
