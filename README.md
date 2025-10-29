🫐 Wild Blueberry Yield Prediction
📘 Project Overview

This project uses machine learning techniques to predict the yield of wild blueberries based on various environmental and pollination-related factors.
The dataset was generated using the Wild Blueberry Pollination Simulation Model, which simulates how bee visits, flower density, and weather conditions affect blueberry yield.

🎯 Problem Statement

The goal is to predict the “yield” (a continuous numeric variable) using the other 17 input features.
The performance of different regression models is compared using RMSE (Root Mean Squared Error) as the main evaluation metric.

⚙️ Models Used
Model	Description
Linear Regression	Baseline model that assumes a linear relationship between features and yield.
Ridge Regression	Adds L2 regularization to reduce overfitting.
Lasso Regression	Adds L1 regularization, which also performs feature selection.
Elastic Net	Combination of Ridge and Lasso methods.
Random Forest Regressor	Ensemble of decision trees that captures non-linear patterns.
Support Vector Regressor (SVM)	Uses kernel trick to fit complex patterns.
XGBoost Regressor	Advanced boosting algorithm that combines multiple weak learners for high accuracy.
🧩 Technologies Used

Python

Pandas, NumPy

Scikit-learn

XGBoost

Matplotlib / Seaborn (optional for visualization)

📊 Evaluation Metric

Root Mean Squared Error (RMSE)

Lower RMSE → Better model performance

🚀 Results Summary (Example)
Model	RMSE (Test)
Linear Regression	133.4
Ridge Regression	150.3
Lasso Regression	141.1
Elastic Net	205.8
Random Forest	147.6
SVM	138.5
XGBoost	120.7 (Best)

✅ The XGBoost Regressor gave the lowest RMSE, meaning it predicted the yield most accurately.

📝 Conclusion

The study shows that advanced ensemble models like XGBoost can effectively capture the complex relationships between environmental factors and blueberry yield.
However, simpler models like Linear Regression also performed reasonably well, indicating the dataset has a strong linear relationship.
