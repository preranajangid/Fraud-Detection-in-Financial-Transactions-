# Fraud Detection in Financial Transactions

This project analyzes 6.3M+ financial transaction records to proactively detect fraudulent activity.  
It was developed as part of a case study challenge.

## 🚀 Key Steps
- Data Cleaning: Missing values, outliers, multicollinearity.
- Exploratory Data Analysis (EDA): Fraud vs non-fraud patterns.
- Feature Engineering: Encoding transaction type, scaling, removing identifiers.
- Models:
  - Logistic Regression (baseline, ROC-AUC 0.99)
  - Random Forest (subset for speed, high recall)
- Evaluation: Classification report, confusion matrix, ROC curve, feature importance.
- Insights: Transaction type, amount, and balance inconsistencies were top predictors.
- Recommendations: MFA, anomaly detection, real-time alerts, regular retraining.

## 📂 Files
- `fraud_detection_case_study.ipynb` – full notebook with code & results
- `Fraud.csv` – dataset (not uploaded due to size, [source link here](https://drive.usercontent.google.com/download?id=1VNpyNkGxHdskfdTNRSjjyNa5qC9u0JyV&export=download&authuser=0))

## 🛠️ Tools & Libraries
Python, Pandas, Numpy, Scikit-learn, Matplotlib, Seaborn, Jupyter
