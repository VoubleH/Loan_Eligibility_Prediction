# Loan Eligibility Prediction

This project aims to predict whether a loan applicant is eligible for loan approval based on financial and personal information, using a Logistic Regression model.

## 📌 Overview
- Dataset with over 1 million rows and 100+ columns
- Preprocessing techniques including:
  - Handling missing values
  - Cleaning and converting categorical features (e.g., `emp_length`)
  - Outlier filtering using quantiles
  - One-hot encoding for categorical variables
- Logistic Regression model
- Threshold tuning and performance comparison

## 📊 Technologies and Libraries Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## 📂 Folder Structure
```
Loan_Eligibility_Prediction/
├── notebook/
│   └── Loan_Eligibility_Prediction.ipynb
├── data/
├── src/
├── requirements.txt
├── README.md
├── .gitignore
```

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
- Cleaned `emp_length` column to retain only numeric years
- Removed extreme outliers in `annual_inc`, `dti`, `revol_util`
- Applied one-hot encoding on categorical features
- Handled missing values using mean or mode where appropriate

## 📈 Model
- Trained Logistic Regression using cleaned and encoded dataset
- Evaluated performance with accuracy and classification report
- Adjusted threshold (e.g., 0.4) to optimize prediction sensitivity

## ✍️ Author
Ben Roshan D
