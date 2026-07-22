# 💳 Cost-Aware Credit Card Fraud Detection Using Machine Learning

## Authors
- **Dr. Pooja Shah**

---

## 📌 Project Overview

Credit card fraud detection is a highly imbalanced classification problem because fraudulent transactions represent less than 1% of all transactions. This project develops a cost-aware fraud detection system using machine learning and advanced feature engineering techniques to accurately identify fraudulent transactions while minimizing business loss.

---

## 🎯 Objectives

- Detect fraudulent credit card transactions.
- Handle severe class imbalance.
- Compare multiple machine learning models.
- Reduce business cost caused by fraud.
- Improve model interpretability using rule-based explanations.

---

## 📊 Dataset

**Source:** Kaggle Credit Card Fraud Detection Dataset

- Training Transactions: **1,296,675**
- Testing Transactions: **555,719**
- Fraud Rate: **0.58%**

Dataset Link:
https://www.kaggle.com/datasets/kartik2112/fraud-detection

---

## 🛠 Feature Engineering

The project includes:

- Transaction amount features
- Temporal features (hour, weekday, weekend)
- Customer age
- Geographical distance
- Sequential transaction behavior
- Merchant risk
- Category risk
- Impossible travel detection
- Merchant text-based features
- Customer transaction history

---

## 🤖 Machine Learning Models

- Logistic Regression
- Random Forest
- Random Forest + SMOTE
- XGBoost
- XGBoost + Rule-Based Threshold
- XGBoost + Bayes Minimum Risk Threshold

---

## 📈 Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- PR-AUC
- ROC-AUC
- Business Cost

---

## 🏆 Best Model

The XGBoost model achieved the best overall performance by providing high fraud detection capability while minimizing business cost.

---

## 💻 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Google Colab

---

## 📁 Repository Contents

- credit-card-fraud-detection.py
- README.md

---

## 📌 Future Improvements

- Deploy as a web application
- Add SHAP explainability
- Real-time fraud detection
- Deep learning implementation

---

⭐ If you found this project useful, feel free to star this repository.
