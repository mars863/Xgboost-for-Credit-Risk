
# XGBoost Credit Risk Prediction

## 📌 Project Overview
This project implements a **Credit Risk Prediction** system using the **XGBoost Classifier** to classify loan applicants as **low-risk** or **high-risk** borrowers. The goal is to help financial institutions make informed lending decisions by predicting the likelihood of loan default.

The project follows a complete machine learning pipeline including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, hyperparameter tuning, and model serialization.

---

## 🎯 Objectives

- Predict the credit risk of loan applicants.
- Compare multiple classification algorithms.
- Select the best-performing model.
- Optimize model performance using hyperparameter tuning.
- Save the trained model for future predictions.

---

## 📂 Dataset

The dataset contains customer information such as:

- Age
- Income
- Loan Amount
- Loan Intent
- Home Ownership
- Loan Grade
- Employment Length
- Credit History Length
- Previous Loan Default Status
- Loan Percentage of Income
- Interest Rate

**Target Variable**

- **0** → Low Risk
- **1** → High Risk

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook / Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib

---

## 🔄 Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Handling Missing Values
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Encoding
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Hyperparameter Tuning
11. Model Serialization

---

## 🤖 Models Compared

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- XGBoost Classifier

**Best Model:** XGBoost Classifier

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## ⚙️ Hyperparameter Tuning

RandomizedSearchCV was used to optimize:

- n_estimators
- max_depth
- learning_rate
- subsample
- colsample_bytree
- gamma

---

## 📈 Results

- Built an optimized XGBoost classification model.
- Improved prediction performance through hyperparameter tuning.
- Evaluated using multiple classification metrics.
- Saved the trained model using Joblib for future use.

---

## 🚀 Future Improvements

- Deploy using Streamlit, Flask, or FastAPI.
- Improve performance with larger datasets.
- Add model monitoring and retraining.

---

## 👨‍💻 Author

**Arshad Alom**

Machine Learning Internship Project
