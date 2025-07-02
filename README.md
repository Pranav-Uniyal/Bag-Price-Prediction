# 👜 Bag Price Prediction - Playground Series S5E2 (Kaggle)

This project is a machine learning regression task based on the Kaggle competition **[Playground Series - Season 5, Episode 2](https://www.kaggle.com/competitions/playground-series-s5e2)**. The goal is to predict the **price of bags** using structured product features.

>  Current best RMSE: `38.26` using **Lasso Regression**

---

##  Model Comparison (RMSE)

| Model                     | RMSE     |
|--------------------------|----------|
| **Lasso Regression**     | 38.26 ✅ |
| Ridge Regression         | 38.27    |
| Linear Regression        | 38.27    |
| Gradient Boosting Regr.  | 38.33    |
| XGBoost Regressor        | 40.46    |
| Decision Tree Regressor  | 55.17 ❌ |

---
## 🧪 Evaluation Metric

The competition uses **Root Mean Squared Error (RMSE)**:
```math
RMSE = sqrt(mean((ytrue - ypred)^2))
```
---
## Contributions
This is an open experimental notebook. Feel free to fork and:

Try different algorithms

Tune the preprocessing pipeline

Explore model stacking or feature engineering

Pull requests are welcome!

---
## Pranav Uniyal



