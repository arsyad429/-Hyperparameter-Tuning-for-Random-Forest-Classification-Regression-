🔧 Hyperparameter Tuning for Random Forest (Classification & Regression)



This project explores and compares three different hyperparameter tuning methods for the **Random Forest** algorithm — both for **classification** and **regression** tasks.

## 📊 Project Overview

We applied and evaluated the following tuning methods:
- ✅ **Grid Search**
- 🎲 **Random Search**
- 🚀 **Optuna (Bayesian Optimization)**

Each method was tested using:
- `RandomForestClassifier` (for classification)
- `RandomForestRegressor` (for regression)

## ⚙️ Model Performance

### 🧠 Classification (Metric: Accuracy)
| Tuning Method | Accuracy |
|---------------|----------|
| Grid Search   | **0.76** |
| Random Search | **0.76** |
| Optuna        | **0.76** |

### 📈 Regression (Metric: Mean Squared Error - MSE)
| Tuning Method | MSE  |
|---------------|------|
| Grid Search   | **0.25** |
| Random Search | **0.25** |
| Optuna        | **0.25** |

> 🔍 **Note:** All methods resulted in the same performance, which indicates the model may have reached a stable optimum under current data and feature settings. Also, I didn't really do all the feature engineering and data cleaning things, because I only want to compare these three methods. So if you want better accuracy from the model, you can try to modify it yourself



