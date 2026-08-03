# Level 1 Task 3: Deliberately Messy Cafe Sales Data Cleaning

## 📌 Overview
This task transforms a degraded, raw, and systematically flawed cafe transactions dataset into an enterprise-ready analytics dataset while maintaining an explicit audit trail.

## 🧹 Cleaning Workflow
* **Data Quality Audit:** Mapped structured `NaN` records alongside concealed textual placeholders (e.g., `"N/A"`, `"missing"`).
* **Imputation Strategy:** Imputed missing `Item` values using category modes and imputed numerical gaps (`Quantity`, `Price Per Unit`) using descriptive medians.
* **Standardization:** Unified text casing, standardized categorical variables, and enforced numeric dtypes.
* **Output:** Exported a fully sanitized dataset (`clean_cafe_sales.csv`).

## 📁 File Reference
* `DhanushKini_Level1_Task3.ipynb`
* `dirty_cafe_sales.csv` - Raw, unclean dataset with missing values and formatting issues
* `clean_cafe_sales.csv` - Final processed and sanitized dataset ready for analysis
