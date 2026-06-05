# Used Car Price Prediction

Machine Learning regression project for predicting used car prices based on vehicle characteristics and technical specifications.

# Project Overview

The goal of this project is to build and compare machine learning models for used car price prediction.

The workflow includes:

- exploratory data analysis (EDA)
- data cleaning and preprocessing
- feature engineering
- handling missing values
- categorical feature processing
- model training and tuning
- model evaluation and interpretation

# Models Used
- Linear Regression
- Random Forest Regressor
- CatBoost Regressor
- LightGBM Regressor

# Best Model Performance
Model:	CatBoost
RMSE: 28945 
R^2: 0.687

# Key Insights
- Mileage was one of the strongest predictors of vehicle price.
- Premium brands significantly increased predicted prices.
- Tree-based boosting models substantially outperformed linear models.
- CatBoost achieved the best overall performance due to effective handling of categorical features.
- 
<img width="961" height="528" alt="Cat_boost_car_importance" src="https://github.com/user-attachments/assets/50c09ef5-35b2-40e6-9a70-aa68f441211c" />

<img width="790" height="790" alt="Real_price_vs_predicted_CatBoost" src="https://github.com/user-attachments/assets/ea257070-39b5-4faa-afb8-a13ee4239d0f" />

# Technologies Used
- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- CatBoost
- LightGBM

# Future Improvements
- SHAP explainability analysis
- sklearn Pipelines
- Cross-validation
- Deployment as a web application
