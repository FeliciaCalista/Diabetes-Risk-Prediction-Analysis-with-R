# Diabetes-Risk-Prediction-Analysis-with-R

## Overview

This analysis explores the relationship between Glucose, BMI, Age, and the probability of having diabetes using logistic regression. Predicted probabilities are visualized to interpret model behavior and assess risk.

### 1. Data Understanding
   - Loading and inspecting the dataset
   - Exploring structure, dimensions, and basic statistics
### 2. Data Quality Check
   - Identifying missing or invalid values
   - Understanding the target variable (Outcome)
### 3. Exploratory Data Analysis
   - Visualizing distributions of key variables (Glucose, BMI, etc.)
   - Comparing feature distributions between diabetic and non-diabetic individuals
   - Investigating correlations between numeric features
### 4. Data Cleaning
   - Converting invalid data points to missing values
   - Imputing missing data using median values
   - Applying log transformation to skewed variables (Insulin)
   - Detecting and addressing outliers
   - Summarizing the cleaned dataset
### 5. Statistical Analysis
   - Testing normality (Shapiro-Wilk)
   - Comparing groups using t-test and Mann-Whitney test
   - Examining associations using Chi-Square test for categorical variables (Age vs Outcome)
### 6. Regression & Prediction
   - Linear Regression: Glucose vs BMI
   - Logistic Regression: Glucose vs Outcome
   - Multivariate Logistic Regression: Glucose, BMI, and Age as predictors
   - Visualizing predicted probabilities of diabetes
   - Interpreting odds ratios, model performance, and ROC-AUC

## Key Insights
- Glucose is the strongest predictor of diabetes, followed by BMI and Age.
- Predicted probabilities confirm risk rises monotonically with glucose levels.
- Multivariate logistic regression provides a well-calibrated, interpretable prediction model (AUC = 0.83).
- Data cleaning and proper handling of missing or invalid values were essential for reliable modeling.
