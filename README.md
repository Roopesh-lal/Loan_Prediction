# 🏦 Loan Prediction using Machine Learning

## 📌 Overview
This project predicts **loan approval status** using machine learning models. It demonstrates data preprocessing, handling class imbalance, training models, evaluating performance, and analyzing feature importance.

## ⚙️ Workflow
- Load dataset (`loan_prediction.csv`)
- Handle missing values (mode for categorical, median for numerical)
- Encode categorical variables with LabelEncoder
- Scale features using StandardScaler
- Balance dataset with **SMOTE**
- Train models:
  - Logistic Regression
  - Random Forest Classifier
- Evaluate with classification report, ROC-AUC, confusion matrix, ROC curve
- Analyze feature importance

## 📊 Results
- **Logistic Regression**
  - Accuracy: 0.76
  - ROC-AUC: 0.75
  - Key feature: Credit_History
- **Random Forest**
  - Accuracy: 0.75
  - ROC-AUC: 0.74
  - Key features: Credit_History, ApplicantIncome, LoanAmount

## 📈 Visualizations
- Confusion Matrices
- ROC Curve comparison
- Feature importance plots
