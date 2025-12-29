# Customer Churn Prediction (Data Science Project)

## 📌 Project Overview
Built an end-to-end machine learning solution to predict customer churn for a telecom company. 
The project covers data understanding, exploratory data analysis, feature engineering, model building,
hyperparameter tuning, and model evaluation using industry-standard metrics.

## 🧠 Business Problem
Customer churn directly impacts revenue. 
The goal of this project is to identify customers likely to churn so that retention strategies can be applied proactively.

## 📊 Dataset
- Source: Telecom customer churn dataset
- Records: ~7,000 customers
- Features: Demographics, account details, services used, and billing information
- Target Variable: `Churn` (Yes / No)

## 🔍 Exploratory Data Analysis
- Analyzed churn distribution across contract types, payment methods, tenure, and monthly charges
- Identified strong churn signals such as month-to-month contracts and higher monthly charges
- Visualized numeric and categorical feature behavior

## ⚙️ Feature Engineering
- Converted target variable to binary
- Applied one-hot encoding for categorical variables
- Scaled numerical features using StandardScaler
- Performed stratified train-test split

## 🤖 Model Building
- Logistic Regression (baseline model)
- Random Forest Classifier (advanced model)
- Evaluated using Accuracy, Confusion Matrix, and ROC-AUC score

## 🚀 Model Optimization
- Tuned Random Forest using GridSearchCV
- Selected best model based on ROC-AUC performance
- Extracted feature importance to explain churn drivers

## 📈 Results
- Random Forest outperformed Logistic Regression
- Achieved strong ROC-AUC score indicating reliable churn prediction
- Identified top churn factors such as contract type, tenure, and monthly charges

## 🛠 Tech Stack
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📌 Key Learnings
- End-to-end machine learning workflow
- Business-oriented model evaluation
- Model explainability using feature importance

## 📎 Future Improvements
- Handle class imbalance using SMOTE
- Deploy model using Flask / FastAPI
- Add real-time prediction dashboard

• Developed an end-to-end customer churn prediction model using Python and machine learning techniques.
• Performed EDA, feature engineering, and model optimization using Logistic Regression and Random Forest.
• Improved churn prediction performance using ROC-AUC evaluation and identified key churn drivers through feature importance analysis.
