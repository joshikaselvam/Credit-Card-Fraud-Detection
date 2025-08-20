# 🏦 Credit Card Fraud Detection (Colab Notebook)

This repository contains a Google Colab notebook for detecting fraudulent credit card transactions using machine learning.  
It includes exploratory data analysis (EDA), data preprocessing, model training, and evaluation.

---

## 📘 Notebook
-  https://colab.research.google.com/drive/1_ft-BTB4wCNtDOnO5hZq4iP0YvcnlPo-?usp=sharing

---

## ✨ Features
- Exploratory Data Analysis on class imbalance and transaction patterns  
- Preprocessing with scaling  
- Machine Learning models (e.g., Logistic Regression, Random Forest)  
- Evaluation with metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC  
- Handles imbalanced dataset effectively  

---

## 📊 Dataset
This project uses the **Credit Card Fraud Detection** dataset (September 2013 European transactions).  
- Available on [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  
- Place the CSV in Colab or mount from Google Drive  
- File required: `creditcard.csv`  

> ⚠️ Dataset is not included in this repository. Please download it separately from Kaggle.  

---

## 🚀 How to Run
1. Open the notebook in Google Colab:
   - Upload the `.ipynb` file  
   - Or directly click: [Open in Colab](https://colab.research.google.com/) and load from GitHub  

2. Install required libraries:
```bash
!pip install pandas numpy scikit-learn matplotlib imbalanced-learn
