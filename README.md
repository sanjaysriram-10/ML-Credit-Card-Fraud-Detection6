# Credit Card Fraud Detection

A machine learning project for detecting fraudulent credit card transactions using various classification algorithms.

## 📌 Project Overview

Credit card fraud is a significant concern in the financial sector, leading to billions of dollars in losses annually. This project leverages machine learning models to accurately classify and detect fraudulent credit card transactions, helping financial institutions prevent unauthorized activity.

## 📂 Dataset

The dataset used for this project is the [Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud), which contains transactions made by European cardholders in September 2013. It presents transactions that occurred over two days, where there are 492 frauds out of 284,807 transactions.

- **Features**: 30 (anonymized for confidentiality, except for `Time` and `Amount`)
- **Class Distribution**: Highly imbalanced (`0`: Non-fraud, `1`: Fraud)

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook (or Google Colab)
- Imbalanced-learn (for handling class imbalance)

## 🧠 Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

## 🧪 Evaluation Metrics

Given the class imbalance, accuracy is not a reliable metric. Therefore, we use:

- Precision
- Recall
- F1-Score
- ROC-AUC Curve
- Confusion Matrix
