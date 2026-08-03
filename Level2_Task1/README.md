# Level 2 Task 1: House Price Prediction (Linear Regression)

## 📌 Overview
This project builds an end-to-end regression pipeline to forecast residential property values using Ordinary Least Squares (OLS) alongside L1 (Lasso) and L2 (Ridge) regularization methods.

## 🛠️ Methodology & Modeling
* **EDA & Feature Engineering:** Evaluated target distributions (Skewness: -0.0644, Kurtosis: -1.2025) and applied One-Hot Encoding to categorical variables (`Location`, `Condition`).
* **Model Benchmarking:** Evaluated baseline OLS regression against Ridge and Lasso models to inspect coefficient shrinkage and mitigate multicollinearity.
* **Diagnostics:** Plotted actual vs. predicted prices and residual distribution plots to check homoscedasticity assumptions.

## 📁 File Reference
* `DhanushKini_Level2_task1.ipynb`
