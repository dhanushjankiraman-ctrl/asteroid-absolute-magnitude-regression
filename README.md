# ☄️ Asteroid Absolute Magnitude Regression

A Machine Learning regression project that predicts asteroid absolute magnitude using asteroid close-approach data.

## 📌 Project Overview

This project applies supervised machine learning regression techniques to an asteroid dataset.

The target variable is:

- `absolute_magnitude`

The project includes data preprocessing, exploratory data analysis, model training, hyperparameter tuning, and model evaluation.

## 🎯 Objective

The main objective is to develop regression models that can predict the absolute magnitude of asteroids based on the available features in the dataset.

## 🧠 Machine Learning Workflow

The project follows these main steps:

1. Data loading
2. Data preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature preparation
5. Train-test split
6. Model training
7. Hyperparameter tuning
8. Model evaluation
9. Model comparison

## 🤖 Models Used

- Linear Regression
- Support Vector Regression (SVR)
- K-Nearest Neighbors (KNN)
- Decision Tree Regressor
- XGBoost Regressor

## 📊 Evaluation Metrics

The models are evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

## ⚙️ Hyperparameter Tuning

RandomizedSearchCV is used for hyperparameter tuning to improve model performance.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## 📁 Project Structure

```text
asteroid-absolute-magnitude-regression/
│
├── asteroid_absolute_magnitude_regression.ipynb
├── README.md
└── .gitignore
