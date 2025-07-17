# Project_energy_predictions

This project focuses on predicting appliance energy consumption using multiple regression models, based on environmental and temporal features from a smart home dataset. The goal is to analyze which machine learning model can best estimate the energy used, helping in energy optimization and smarter energy management systems.
Target Variable: Appliances – representing energy consumed in Wh.
STEPS USED IN THIS PROJECT
1. Preprocessing:

Missing value handling
Log transformation
One-hot encoding for categorical features
Feature scaling (for models like SVR)
Exploratory Data Analysis: Correlation matrix and feature importance visualizations

2.Models Used:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor (SVR)
Hyperparameter Tuning: Conducted on Random Forest using GridSearchCV

3.Evaluation Metrics:

R² Score
RMSE (Root Mean Square Error)
MAE (Mean Absolute Error)

4. Conclusion:
The Random Forest Regressor (with hyperparameter tuning) provided the best balance between prediction accuracy and robustness. While the overall R² score was moderate (~0.70), this is acceptable in real-world applications where appliance usage can be influenced by unpredictable human behavior.

This project demonstrates the end-to-end workflow of a regression task, from data preprocessing and feature analysis to model tuning and evaluation.

