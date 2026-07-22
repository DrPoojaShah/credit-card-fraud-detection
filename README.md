# 💳 Cost-Aware Credit Card Fraud Detection Using Machine Learning

**Author:** Dr. Pooja Shah

## 📌 Project Overview

Credit card fraud causes billions of dollars in financial losses every year. Detecting fraudulent transactions is challenging because fraud cases represent only a very small percentage of all transactions.

This project develops a cost-aware fraud detection system using machine learning techniques. The workflow combines feature engineering, class imbalance handling, model comparison, threshold optimization, and business-cost analysis to identify fraudulent transactions while minimizing financial loss.

---

## 🎯 Objectives

- Detect fraudulent credit card transactions with high recall.
- Compare multiple machine learning models.
- Handle severe class imbalance.
- Engineer behavioral, temporal, geographic, and merchant-risk features.
- Evaluate models using both statistical metrics and business cost.
- Provide interpretable fraud explanations.

---

## 📊 Dataset

- Source: Kaggle Credit Card Fraud Dataset
- Training data: `fraudTrain.csv`
- Testing data: `fraudTest.csv`
- Highly imbalanced binary classification problem.

---

## 🔄 Project Workflow

```
Raw Data
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Feature Engineering
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Business Cost Analysis
      ↓
Fraud Explanation
```

---

## 🛠 Feature Engineering

This project creates several feature groups:

- Transaction amount features
- Temporal features
- Customer age
- Home-to-merchant distance
- Sequential transaction behavior
- Merchant risk
- Category risk
- Impossible travel detection
- Merchant text-based risk indicators

---

## 🤖 Machine Learning Models

The following models were implemented and compared:

- Logistic Regression
- Random Forest
- Random Forest + SMOTE
- XGBoost (Final Selected Model)

---

## 📈 Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- PR-AUC
- Confusion Matrix
- Business Cost

---

## 💰 Cost-Aware Decision Making

Instead of relying only on classification accuracy, this project estimates business impact using:

- False Positive Cost
- False Negative Cost
- Rule-based thresholds
- BMR-inspired dynamic thresholds

This approach makes the model more practical for real-world fraud detection.

---

## 📷 Results

*(We'll insert figures here in the next step.)*

- Class Distribution
- Confusion Matrix
- Precision–Recall Curve
- ROC Curve
- XGBoost Feature Importance
- Model Comparison

---

## 💼 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Imbalanced-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🚀 Repository Structure

```
credit-card-fraud-detection/
│
├── notebooks/
├── src/
├── images/
├── reports/
├── data/
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🔮 Future Improvements

Possible future enhancements include:

- Deep learning models
- Graph Neural Networks
- Real-time fraud detection
- Explainable AI (SHAP/LIME)
- Model deployment using FastAPI or Streamlit

---

## 📄 License

This project was developed for educational and research purposes.
