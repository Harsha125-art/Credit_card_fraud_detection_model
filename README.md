# 🛡️ Credit Card Fraud Detection - ML Project

Welcome!  
This project is about detecting **fraudulent credit card transactions** using real-world data and machine learning.

I completed this as part of my learning journey , and this is one of my first end-to-end practical projects.

---

## 📌 Project Goals

- ✅ Detect whether a transaction is **fraud or not**
- ✅ Build a **highly accurate and sensitive model** for real-time fraud detection
- ✅ Apply what I learned about:
  - Classification
  - Handling imbalanced data
  - Model evaluation
  - Threshold tuning

---

## 📂 Dataset

- 📥 **Source**: [Credit Card Fraud Detection – Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 🔢 **Total Transactions**: 284,807  
- ⚠️ **Fraud Cases**: 492  
- ⚖️ Highly **imbalanced dataset**
- 🔐 Features `V1` to `V28` are anonymized via PCA
- Other features: `Amount`, `Time`, `Class` (target variable: 0 = Not Fraud, 1 = Fraud)

---

## 🧠 What I Learned

- How to deal with **imbalanced classification problems**
- Training with:
  - ✅ **Random Forest**
  - ✅ **XGBoost**
- Using `.predict_proba()` for **custom thresholding**
- Evaluating models using:
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1)
  - ROC Curve & AUC Score

---

## ✅ Final Model Performance

- **Model Used**: XGBoost Classifier
- **Custom Threshold**: `0.3`

| Metric                 | Value   |
|------------------------|---------|
| Accuracy               | 100%    |
| Precision (Fraud = 1)  | 0.91    |
| Recall (Fraud = 1)     | 0.89    |
| F1-Score (Fraud = 1)   | 0.90    |
| ROC AUC Score          | 0.9826  |

## 📊 Tools & Libraries Used

- Python 🐍
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn
- Joblib (to save the model)

---

## 🧪 How to Run the Project

1. **Clone** this repository
2. Open the notebook (`.ipynb`) in Jupyter or any notebook environment
3. Run the cells step-by-step
4. You can **adjust the custom threshold** and observe how model performance changes

---

## 🙋‍♀️ About Me

I'm a student learning Machine Learning and hands-on projects.  
This was one of my first complete ML projects, and I’m excited to share it with others!

---

