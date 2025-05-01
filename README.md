# 🏦 Bank Customer Churn Prediction

This project offers a complete machine learning pipeline to predict **bank customer churn** using structured customer data. It includes everything from EDA and feature engineering to model training, interpretability (SHAP), batch scoring, and deployment-ready outputs.

---

## 📊 Dataset Information

- **Source**: [Bank Customer Churn Dataset – Kaggle](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset)
- **License**: Open use on Kaggle
- **Contents**: 10,000 customer records including demographics, account behavior, product usage, and churn status

---

## 📍 Project Features

- 📊 Exploratory Data Analysis (EDA)
- 🎯 Model training: Logistic Regression, Random Forest, and Gradient Boosting
- 🛠️ Hyperparameter tuning with GridSearchCV
- 🔍 Explainability using SHAP values
- 👤 Interactive prediction form (single client)
- 📋 Batch churn prediction via CSV/Google Sheets template
- 📥 Downloadable prediction output

---

## 💻 How to Run This Notebook in Google Colab

1. Visit [Google Colab](https://colab.research.google.com/)
2. Click **File → Upload Notebook**
3. Select the notebook file: `bank_customer_churn_prediction2025.ipynb` from this repo
4. Once it loads in Colab, continue below 👇

### 🚨 IMPORTANT: Install Required Dependencies

Before running anything, **manually install all necessary packages** by adding and running this cell at the top of the notebook:

```python
# ✅ Install required packages
!pip install --upgrade pip
!pip install ipywidgets shap scikit-learn pandas matplotlib seaborn
