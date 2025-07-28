💳 Fraud Detection ML Model

Accredian Screening Assignment

📌 Project Overview

This project presents a Fraud Detection Pipeline designed to identify and analyze fraudulent financial transactions from a dataset of 6.3 million entries. It was built as part of the Accredian Data Science Researcher Screening Assignment.

The goal was to build a **robust, interpretable, and high-performing ML model** that can detect fraudulent behavior early, provide insights, and support infrastructure improvements to minimize future risks.

🔍 Problem Statement

Financial fraud is a persistent threat to businesses and users. Detecting fraud in real-time, especially in large-scale datasets, is crucial. The key challenges include:

* High class imbalance (fraud cases are rare)
* Similarity of fraud and genuine transaction patterns
* Need for both high recall and model interpretability

🧠 ML Solution Highlights

 *Model Used: XGBoost Classifier
 *Imbalance Handling: SMOTE & class-weight tuning
 *Preprocessing:

  * Outlier reduction
  * Multicollinearity checks (VIF)
  * Log transformation of skewed features
    
 🏆Performance:

  * 95% Recall on fraud transactions
  * Balanced precision-recall trade-off
    
  📊 Explainability:

  * Feature importance analysis
  * SHAP summary plots for model interpretability

 📌 Key Findings & Insights

🔎 Fraudulent transactions often involve:
  * Unusually large amounts
  * Abnormal balances before/after the transaction
  * Certain transaction types (e.g., 'TRANSFER', 'CASH\_OUT')

 🔄 Balance pattern anomalies:

  * Fraud cases show sharp balance drops inconsistent with normal behavior.

  🔐Infrastructure suggestions:
  Proposed system upgrades that could reduce fraud risk by 70%, such as:
  * Real-time transaction monitoring
  * User-level behavioral fingerprinting
  * Early warning score triggers

 ⚙️ Tech Stack
* Python
* Pandas, NumPy
* Scikit-learn, XGBoost
* Imbalanced-learn (SMOTE)
* SHAP
* Matplotlib, Seaborn

📈 Model Evaluation Metrics

| Metric        | Value |
| ------------- | ----- |
| Recall        | 0.95  |
| Precision     | 0.89  |
| F1-Score      | 0.92  |
| ROC-AUC Score | 0.98  |

🙋‍♂️ Author
Md Rehan Hussain
Data Science Enthusiast | Python | ML | AI
[LinkedIn](https://linkedin.com/in/md-rehan-hussain) • [GitHub](https://github.com/rehanraza19)

📌 Acknowledgement

This project was developed as part of the Accredian Screening Assignment for the Data Science Internship role.
