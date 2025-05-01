# 🛒 E-Commerce Customer Churn Forecast and Analysis

![banner](https://your-banner-source.com/banner.png)

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Last Commit](https://img.shields.io/github/last-commit/your-username/your-repo)
![Machine Learning](https://img.shields.io/badge/ML-Type-Classification-orange)
![License](https://img.shields.io/github/license/your-username/your-repo)

## 🔍 Business Problem

Understanding and predicting customer churn is crucial in e-commerce or in any industry to reduce loss and improve retention strategies. This project analyzes customer behavior to forecast churn and guide data-driven decisions.

## 📊 Key Insights

> 🔸 Most churned customers showed inactivity in last 30 days.  
> 🔸 High-value customers rarely churn unless delivery time increases.  
> 🔸 Increased frequency of returns correlates with churn risk.  
> 🔸 XGBoost outperformed other models with balanced precision and recall.

---

## 🧠 Key Features

- ✅ End-to-end ML pipeline from preprocessing to model evaluation.
- ✅ Automated model training & metric logging.
- ✅ Customer behavior insights via advanced EDA.
- ✅ Highly optimized churn predictor with AUC score of 0.97.

---

## ⚙️ Tech Stack

- **Python** (3.10+)
- **Pandas**, **NumPy**
- **Seaborn**, **Matplotlib**
- **XGBoost**, **Scikit-learn**
---
## 🔬 Methods

### 🔹 Outlier Handling
- Used **IQR** method and **Box Plots** to detect and handle statistical outliers in numeric features.

### 🔹 Customer Behaviour Analysis
- Conducted **univariate and bivariate analysis**.
- Aggregated data by churn label to detect behavior patterns.

### 🔹 Feature Engineering & Correlation
- Generated new features like **purchase frequency**, **engagement score**.
- Detected multicollinearity using **Variance Inflation Factor (VIF)**.
- Performed **target encoding** for categorical features.

### 🔹 Model Training & Evaluation
- Built reusable functions to train and evaluate models.
- Trained models: **Logistic Regression**, **Random Forest**, **XGBoost**.
- Best model: **XGBoost Classifier** with:
  - **Accuracy:** 0.94
  - **AUC Score:** 0.97
  - **Recall optimized for churned class**

### 🔹 Threshold Tuning & Metric Optimization
- Lowered probability threshold to increase recall.
- Visualized results with **ROC**, **confusion matrix**, and **precision-recall curves**.

---

## 📌 License

This project is licensed under the [MIT License](LICENSE).
---
Made with ❤️ by [Adin](https://github.com/adin11)
