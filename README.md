# 🔬 Ms Temperature Prediction in HSLA Steels

**Undergraduate Project (MSE497) | IIT Kanpur**  
**Supervisor:** Prof. Amarendra Kumar Singh

---

## 📘 Project Overview

This project aims to develop a **data-driven machine learning framework** to predict the **Martensite Start Temperature (Ms)** of **High-Strength Low-Alloy (HSLA)** steels using their chemical composition. By leveraging various ML algorithms and ensemble learning methods, the model provides accurate and interpretable predictions aligned with metallurgical understanding.

---

## ⚙️ Approaches Used

- 🔎 **Data Preprocessing & Curation**  
  - Removed outliers (especially high-Nickel compositions) to improve interpretability  
  - Applied z-score normalization for model readiness

- 🧠 **ML Models Explored**  
  - Linear Regression, Decision Trees, Random Forest  
  - Gradient Boosting, XGBoost (Grid Search + Optuna), SVM  
  - ANN (MLPRegressor), Stacking Ensemble

- 🤖 **Ensemble Learning Techniques**  
  - Bagging, Boosting, Stacking  
  - Final model used: **Stacked Ensemble** of XGBoost + MLP + GBR + Extra Trees with Linear Regression as meta-learner

---

## 📈 Final Model Performance

| Metric | Value |
|--------|-------|
| **R² Score** | 0.9018 |
| **Mean Absolute Error (MAE)** | 17.06 K |

✅ Improved generalization  
✅ Interpretability aligned with metallurgical theory  
✅ Final model outperformed individual regressors

---

## 📄 Report

You can view/download the full project report here:  
👉 [**UGP Final Report (PDF)**](./UGP.pdf)

---

## 🛠️ Tech Stack

- Python (pandas, scikit-learn, xgboost, optuna)
- Jupyter Notebook
- Matplotlib / Seaborn (visualization)

---

## 📬 Contact

For queries, feel free to reach out:  
📧 gprashant22@iitk.ac.in  

---

> _"Bridging machine learning with metallurgy for smarter alloy design."_ ⚙️🔍
