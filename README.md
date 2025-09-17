# 💳 Credit Card Fraud Detection

A machine learning project to detect fraudulent credit card transactions using anomaly detection techniques.

---

## 📖 Overview
Credit card fraud is a major concern for banks and customers.  
This project applies **unsupervised machine learning methods** to identify fraudulent transactions in a highly imbalanced dataset.  

We use three anomaly detection algorithms:
- **Isolation Forest**
- **Local Outlier Factor (LOF)**
- **One-Class SVM**

---

## 📊 Dataset
- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- **Transactions**: 284,807  
- **Fraudulent cases**: 492 (~0.172%)  
- **Features**: 30 (PCA-transformed V1–V28, plus `Time` and `Amount`)  

⚠️ Dataset is highly imbalanced, which makes fraud detection challenging.

---

## ⚙️ Methodology
1. **Data Preprocessing**
   - Removed null values, analyzed class distribution.
   - Visualized transaction amounts and time distribution.
   - Used a 10% sample for faster computation.

2. **Exploratory Analysis**
   - Transaction class imbalance visualization.
   - Heatmap for feature correlation.

3. **Modeling**
   - Applied **Isolation Forest**, **LOF**, and **One-Class SVM**.
   - Predicted anomalies vs. normal transactions.

4. **Evaluation Metrics**
   - Accuracy
   - Precision, Recall, F1-score
   - Classification Report

## 📈 Results
- **Isolation Forest** → Accuracy ~99%, good fraud detection.  
- **Local Outlier Factor** → Accuracy ~99%, slightly more false positives.  
- **One-Class SVM** → Accuracy ~97%, less efficient on large, imbalanced data.  

�

