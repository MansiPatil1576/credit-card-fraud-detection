 credit-card-fraud-detection
A machine learning project to detect fraudulent transactions using Python.

## 📌 Overview
This project applies machine learning techniques to identify fraudulent credit card transactions.  
The dataset is highly imbalanced, so techniques like resampling and proper evaluation metrics are used.

## 📊 Dataset
- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Contains transactions made by European cardholders in September 2013.
- Features: 30 (V1–V28, Amount, Time)
- Total transactions: 284,807  
- Fraudulent transactions: 492 (≈0.172%)

## ⚙️ Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/credit-card-fraud-detection.git
2.Install dependencies:
   pip install -r requirements.txt
3.Usage
Run the Jupyter Notebook to train and evaluate the model:
jupyter notebook fraud_detection.ipy
