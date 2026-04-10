# AutoValuate AI: Car Price Prediction & Analysis

![Project Header](https://img.shields.io/badge/ML-Regression-blue.svg) 
![Python](https://img.shields.io/badge/Python-3.8%2B-green.svg)

## 📌 Project Overview
**AutoValuate AI** is an end-to-end Machine Learning pipeline designed to estimate the market value of used cars. By analyzing technical specifications and usage history, this project identifies the key factors that drive vehicle depreciation and valuation in the modern market.

## 📊 Dataset Description
The model is trained on a dataset of 2,000 entries with the following features:
- **Brand:** Toyota, Honda, Ford, BMW, Hyundai, Tesla.
- **Model Year:** Year of manufacture (2005 – 2023).
- **Engine Size:** Engine capacity in liters.
- **Horsepower:** Engine power output.
- **Mileage:** Total distance driven.
- **Fuel Type:** Petrol, Diesel, Electric, Hybrid.
- **Transmission:** Manual, Automatic.
- **Price (Target):** Current market value.

## 🛠️ Tech Stack
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn
- **Visualization:** Matplotlib, Seaborn
- **Modeling:** Linear Regression, Random Forest, Gradient Boosting, MLP Neural Networks

## 🚀 Project Workflow
1. **EDA:** Analyzed correlation matrices and distribution plots to identify price drivers.
2. **Preprocessing:** Handled categorical encoding (One-Hot) and feature scaling (Standardization).
3. **Modeling:** Trained and cross-validated four regression models.
4. **Evaluation:** Benchmarked models using RMSE and R² scores.

## 📈 Results
The **Linear Regression** model outperformed complex ensembles, achieving:
- **R² Score:** 0.9665 (96.6% accuracy)
- **RMSE:** $1,663.28



**Key Insight:** Horsepower and Model Year are the strongest indicators of price, while Mileage acts as the primary depreciating factor.
