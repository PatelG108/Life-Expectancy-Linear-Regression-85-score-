# 🌏 Life Expectancy Prediction using Linear Regression

[![Kaggle Score: 85%](https://img.shields.io/badge/Kaggle-85%25-brightgreen)](https://www.kaggle.com/code/amit8021/life-expectancy-with-linear-regression-85-score)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://www.linkedin.com/in/amit-kumar-c/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Predicting **life expectancy** is a crucial task for public health, policy-makers, and researchers. This project demonstrates how to build a **machine learning pipeline** to forecast life expectancy using real-world WHO data, achieving a strong R² score of **0.85**.

---

## 🚀 Project Highlights

- **Real WHO Dataset:** Multiyear, multi-country, 22 features.
- **Robust Data Cleaning:** Mean-imputation, outlier handling with IQR.
- **Feature Engineering:** Label encoding, MinMax scaling, clear handling of categorical and numerical columns.
- **Model Building:** Linear Regression with train-test split and R² score evaluation.
- **Rich Visualizations:** Interactive Plotly plots—boxplots, heatmaps, trends, and comparisons.
- **Generalization Check:** Overfitting/underfitting inspection.

---

## 📊 Workflow

1. **Data Loading & Overview**
    - Import dataset, shape and info summary.
    - Descriptive stats and missing value analysis.

2. **Cleaning & Imputation**
    - Mean-value fill for missing numeric data.
    - Outlier detection/replacement using IQR.

3. **Exploratory Data Analysis**
    - Plots: year-wise, status-wise, country-wise.
    - Correlation heatmap.

4. **Feature Encoding & Scaling**
    - Label Encoding for categorical data.
    - MinMaxScaler for numerical features.

5. **Model Development**
    - Train/Test split (80/20).
    - Train Linear Regression, predict, score with R².

6. **Results Visualization**
    - Scatter plots for actual vs predicted values.
    - Comparisons: Developed vs Developing countries.

---

## 📈 Results

- **Final Model:** Linear Regression
- **Score:** R² = 0.85
- **Insights:**
    - GDP and healthcare spending strongly correlated with life expectancy.
    - Developed nations have higher, less variable life expectancy.
    - Proper outlier and missing data handling improves predictions.

---

## 🖼️ Example Visualizations

- Boxplot: Outlier detection (pre/post cleaning)
- Correlation heatmap
- Life expectancy trend per country
- Status histogram (Developed vs Developing)

---

## 🔧 Usage

Clone and run the notebook on Kaggle or locally:

---


## 🙋‍♂️ Author

- **Amit Kumar**
- [![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin)](https://www.linkedin.com/in/amit-kumar-c/)
