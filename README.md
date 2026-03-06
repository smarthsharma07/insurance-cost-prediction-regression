# Insurance Cost Prediction using Regression

This project predicts medical insurance charges using demographic and lifestyle data.

The notebook demonstrates a complete machine learning workflow including data exploration, preprocessing, regression modeling, and model evaluation.

---

## Problem Statement

Medical insurance costs depend on multiple factors such as age, body mass index (BMI), smoking habits, and demographic information.

The goal of this project is to build a regression model that predicts medical insurance charges using these features.

---

## Dataset

The dataset contains **1338 records** with the following features:

| Feature | Description |
|------|------|
| age | Age of the individual |
| sex | Gender |
| bmi | Body Mass Index |
| children | Number of dependents |
| smoker | Smoking status |
| region | Residential region |
| charges | Medical insurance cost (target variable) |

---

## Project Workflow

The following steps were performed:

1. Data loading and inspection
2. Missing value analysis
3. Exploratory Data Analysis (EDA)
4. Numerical feature analysis
5. Categorical feature analysis
6. Feature encoding using One-Hot Encoding
7. Correlation analysis
8. Train-test split
9. Feature scaling
10. Baseline Linear Regression model
11. Residual analysis
12. Regularized regression models
13. Hyperparameter tuning
14. Final model evaluation

---

## Exploratory Data Analysis

EDA revealed several important insights:

- **Smoking status strongly influences insurance charges**
- Charges are **right-skewed**, with some individuals having very high medical costs
- Age and BMI show moderate correlation with insurance charges
- Region and gender have weaker influence

---

## Models Used

The following regression models were explored:

### Linear Regression
Baseline model used for comparison.

### Ridge Regression
L2 regularization applied to improve model stability.

### Lasso Regression
L1 regularization used to shrink less important coefficients.

---

## Model Performance

| Model | RMSE | R² |
|------|------|------|
| Linear Regression | ~5796.284 | ~0.7835 |
| Ridge Regression | ~5796.35 | ~0.7835 |
| Lasso Regression | ~5796.288 | ~0.7835 |

The final model selected was **Ridge Regression with α = 0.1**.

---

## Key Insights

- Smoking status is the **strongest predictor of insurance charges**
- Age and BMI also influence medical costs
- Regularization improves model stability and predictive performance

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---
## Files 
- medical_insurance.csv is the dataset
- medical insurance charges predictor - regression.ipynb is the jupyter notebook with the full workflow of this project.

## Future Improvements

Possible improvements for this project include:

- Tree-based models (Random Forest, Gradient Boosting)
- Feature interaction engineering
- Cross-validation for model robustness

---


## Author
Smarth Sharma
- Machine Learning regression project exploring EDA and regularization techniques for cost prediction.

## Project Structure
