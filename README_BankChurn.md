# 🏦 Predicting Customer Churn in Retail Banking

This project analyzes customer churn in the banking industry using predictive modeling techniques including logistic regression, decision trees, and random forests. By identifying key factors influencing churn, we provide insights that help banks proactively retain high-risk customers.

## 📌 Project Summary

**Team Members:**  
Raheela Charania, Anmol Anchala, Emmanuel Wediko

**Course:**  
BDA 620: Data Mining, Mercer University  
**Instructor:** Dr. Eshan Ahmadi  
**Date:** December 12, 2024

## 🧠 Objective

To develop accurate and interpretable models that predict whether a bank customer will churn, enabling data-driven retention strategies.

## 🔍 Methodology

- **Exploratory Data Analysis (EDA):** Outlier detection, distribution analysis  
- **Data Preprocessing:** Dummy variable creation, z-score standardization, outlier removal  
- **Modeling Techniques:**
  - Logistic Regression (Stepwise Selection)
  - Decision Tree (CART)
  - Random Forest
  - K-Nearest Neighbors (KNN)

## 📊 Key Findings

- Age, balance, and number of products are the top predictors of churn.
- Random Forest achieved the highest AUC (0.85) and was the most robust model.
- Overfitting was addressed by removing highly correlated variables like complaints.

## ✅ Recommendations

- Target mid-aged customers (40–52) with lifestyle-based promotions.
- Offer retention incentives to high-balance customers.
- Encourage product bundling to reduce churn probability.

## 📈 Performance Metrics

| Model             | Accuracy | AUC   | Sensitivity | Specificity |
|------------------|----------|-------|-------------|-------------|
| Logistic Reg.     | 71.7%    | 79.6% | 73.5%       | 69.9%       |
| CART              | 79.7%    | 83.2% | 81.9%       | 71.2%       |
| Random Forest     | 83.8%    | 85.5% | 89.3%       | 62.2%       |
| KNN               | 83.5%    | 83.7% | 68.4%       | 99.0%       |

## 📚 References

- de Lima Lemos et al., 2022. Neural Computing & Applications  
- Kissell & Poserina, 2017. Optimal Sports Math  
- Martinez-Taboada et al., 2020. PLOS ONE  
- Capgemini World Retail Banking Report, 2019

---

📁 For full documentation, model code, and visualizations, see the repository folders.