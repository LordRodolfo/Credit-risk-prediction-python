# 🏦 Credit Risk Classification Project
**Author:** Rodolfo | Statistician & Data Scientist

## 📌 Project Overview
This project develops a machine learning pipeline to predict the probability of loan default. As a Statistician, I focused on ensuring the model is not only predictive but also statistically sound and parsimonious.

## 🛠️ Data Science Pipeline
1. **Data Auditing:** Cleaned outliers (e.g., ages of 144 years) and handled missing values in interest rates.
2. **Feature Engineering:** Implemented One-Hot Encoding and Standard Scaling to ensure gradient descent convergence.
3. **Statistical Pruning:** Used `statsmodels` to evaluate **p-values**, removing non-significant features (Age, Credit History Length) to reduce model complexity.
4. **Implementation:** Built a real-time prediction script to simulate bank credit scoring.

## 📊 Performance
- **Accuracy:** 86%
- **Recall (Default):** 55% (Optimized for banking risk sensitivity)
- **Status:** Fully Operational script for new applicant scoring.
