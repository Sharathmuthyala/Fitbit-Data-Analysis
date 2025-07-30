# 📊 Sleep and Readiness Score Analysis

This repository contains two data science projects that analyze wellness metrics using data from wearable devices:

- **`Readiness Score Report.pdf`**  
- **`Sleep Score Report.pdf`**

These projects use statistical analysis, data visualization, and machine learning to understand how daily activity, sleep patterns, and heart rate variability impact readiness and sleep quality.

---

## 📁 Files

| File                         | Description                                                      |
|-----------------------------|------------------------------------------------------------------|
| `Readiness Score Report.pdf`| Final report analyzing daily readiness scores with regression and ML models |
| `Sleep Score Report.pdf`    | Final report exploring sleep data and classifying sleep quality using multiple models |

---

## 🔍 Project 1: Readiness Score Report

This project explores the relationship between **readiness score** and its contributing subcomponents:

### 📈 Features:
- `readiness_score_value`, `activity_subcomponent`, `sleep_subcomponent`, `hrv_subcomponent`
- Time-series and correlation analysis

### 🧪 Methods:
- **Linear & Polynomial Regression**
- **Decision Tree & Random Forest**
- **K-Nearest Neighbors (KNN)**

### 🏆 Results:
- Best RMSE: **KNN (RMSE ≈ 9.06)**
- Strong positive influence of activity and sleep scores on readiness
- HRV showed minimal statistical significance

---

## 🌙 Project 2: Sleep Score Report

This project models **overall sleep score** based on features like composition, duration, revitalization, deep sleep, and restlessness.

### 📊 Features:
- `overall_score`, `composition_score`, `duration_score`, `deep_sleep_in_minutes`, `resting_heart_rate`, `restlessness`

### 🧪 Methods:
- **Regression Models**: Linear, Ridge, Lasso
- **Classification Models**: Decision Tree, SVM, Naive Bayes
- **EDA & Correlation Plots**

### 🏆 Results:
- **SVM & Decision Tree achieved 100% accuracy**
- Ridge Regression: **RMSE = 0.92**, **R² = 0.99**
- Restlessness and revitalization scores were strong indicators of sleep quality

---

## 🛠️ Technologies Used

- R (RStudio)
- `tidyverse`, `caret`, `tidymodels`, `ggplot2`, `randomForest`, `rpart`, `e1071`, `glmnet`, `corrplot`

---

## 📌 Notes

- The datasets are derived from wearable fitness trackers and were anonymized for privacy.
- These analyses are academic projects and are not intended for clinical or diagnostic use.

---
