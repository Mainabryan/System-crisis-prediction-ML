# 🧠 Predicting Systemic Crises in African Countries (1860–2014)

## 📌 Project Overview

This machine learning project uses historical economic data from 13 African countries to predict whether a **systemic financial crisis** will occur. The aim is to build a classification model that learns patterns from indicators like **inflation rates** and predicts the likelihood of a crisis.

---

## 🌍 Dataset Description

- **Source:** Kaggle (Image preview: [link](https://i.imgur.com/3XzFz3x.jpg))
- **Countries:** Algeria, Angola, Egypt, Kenya, Nigeria, South Africa, Zimbabwe, etc.
- **Years Covered:** 1860 – 2014
- **Main Crises Tracked:**
  - Systemic Crisis (Target variable)
  - Banking Crisis
  - Debt Crisis
  - Inflation Crisis
- **Other Variables:** Annual inflation rate, year, country, etc.

---

## 🎯 Objective

> **Predict whether a country will experience a systemic crisis** based on economic indicators.

This is a **binary classification** task (Yes = 1, No = 0).

---

## ✅ Workflow Summary

1. **Data Loading & Exploration**
   - Display data shape, types, null values
   - Generate profiling report

2. **Data Cleaning**
   - Handle missing values
   - Remove duplicates
   - Encode categorical features
   - Handle outliers

3. **Feature Selection**
   - Define target: `systemic_crisis`
   - Select meaningful features (like inflation rate, year)

4. **Data Splitting**
   - Train/Test split (e.g., 80/20)

5. **Modeling**
   - Train ML models (Logistic Regression, Random Forest, etc.)
   - Use best model based on evaluation

6. **Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion matrix

---

## 📈 Expected Outcome

- A trained classification model that can **predict the emergence of a systemic crisis**.
- Insights on how economic indicators relate to financial collapses.

---

## 🧠 Future Improvements

- Try other ML algorithms (XGBoost, SVM)
- Add feature scaling or engineering
- Use time-based cross-validation for historical data

---

## 🤝 Team Discussion

The results can be improved by:
- Hyperparameter tuning
- Adding more country-specific financial features
- Handling class imbalance if present

---

## 👨‍💻 Author

**Bryan Waweru**  
Data Science & ML Enthusiast | Kenya  
