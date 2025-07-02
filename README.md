# Predicting Systemic Financial Crises in African Countries (1860–2014)

## Project Overview

This project applies machine learning techniques to analyze historical economic data from 13 African countries. The goal is to build a predictive model that identifies the likelihood of a systemic financial crisis based on key indicators such as inflation rates and crisis history.

This work demonstrates practical skills in data cleaning, feature engineering, model selection, and evaluation—applying machine learning in a real-world policy and economic setting.

## Dataset Description

The dataset includes records from 1860 to 2014, covering:
- Crisis types: Systemic, Banking, Inflation, and Debt crises
- Economic indicators: Annual inflation rates and more
- Countries: Algeria, Angola, Egypt, Kenya, Nigeria, South Africa, Zimbabwe, and others

The target variable is whether or not a **systemic crisis** occurred in a given country-year.

## Key Steps

1. **Data Exploration**
   - Reviewed structure, data types, and missing values
   - Generated data profiling report for quick insights

2. **Data Cleaning**
   - Handled missing values and duplicates
   - Encoded categorical variables
   - Addressed outliers

3. **Feature Selection**
   - Identified relevant predictors (e.g., inflation, country, year)
   - Defined `systemic_crisis` as the target variable

4. **Model Training**
   - Split data into training and test sets
   - Applied and evaluated classification models (e.g., logistic regression, random forest)

5. **Evaluation**
   - Measured accuracy, precision, recall, and F1-score
   - Interpreted results and identified ways to improve

## Outcome

The final model provides an early warning signal for financial instability, based on past trends and economic signals. This has potential value in government planning, financial sector policy, and academic research.

## Future Improvements

- Incorporate additional macroeconomic features
- Explore time-series approaches
- Tune hyperparameters and test more advanced models
