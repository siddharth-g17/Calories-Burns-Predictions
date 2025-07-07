# Calories Burnt Detection using Machine Learning

This project aims to predict the number of calories burnt based on physical and biometric features such as age, gender, height, weight, duration of exercise, heart rate, and body temperature. It uses machine learning models to provide accurate predictions that can help in health tracking and fitness planning.

## Objectives

- Predict calories burned using available features.
- Understand the impact of biometric and workout-related data on calorie expenditure.
- Build and evaluate regression models for prediction.

## Technologies Used

- Python
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (Linear Regression, Random Forest, Decision Tree, XGBoost)

## Dataset Features

The dataset includes inputs like age, gender, height, weight, duration, heart rate, body temperature, and the target variable: calories burned.

## Steps Performed

1. Data cleaning and preprocessing
2. Exploratory data analysis
3. Feature encoding and scaling
4. Model training using regression algorithms
5. Evaluation using metrics like MAE, MSE, and R² score
6. Final predictions and comparison of model performances

## Results

The Random Forest Regressor gave the best performance with high prediction accuracy. The most important features for predicting calories were exercise duration, heart rate, body temperature, and weight.

## Future Scope

- Deploy as a web app for user-friendly predictions
- Connect with real-time health data from wearables
- Add support for activity type (running, walking, cycling)

## How to Run

1. Clone the repository
2. Open the notebook in Jupyter or VS Code
3. Run all cells after installing dependencies
