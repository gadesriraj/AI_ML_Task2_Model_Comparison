# AI_ML_Task2_Model_Comparison
# AI & ML Task 2: Feature Engineering, Model Optimization & Performance Comparison

## Overview

This project focuses on improving a House Price Prediction system using the California Housing Dataset. The project demonstrates data preprocessing, feature engineering, feature scaling, model training, evaluation, and performance comparison of multiple machine learning models.

## Objectives

* Perform data preprocessing and cleaning
* Handle missing values
* Apply feature engineering techniques
* Perform feature scaling using StandardScaler
* Train multiple regression models
* Compare model performance using evaluation metrics
* Select the best-performing model

## Dataset

California Housing Dataset

Target Variable:

* Median House Value

Features:

* Median Income
* House Age
* Average Rooms
* Average Bedrooms
* Population
* Average Occupancy
* Latitude
* Longitude
* Ocean Proximity

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Data Preprocessing

The following preprocessing steps were performed:

1. Missing value detection
2. Median imputation for missing values
3. One-Hot Encoding for categorical features
4. Feature scaling using StandardScaler
5. Train-Test Split (80:20)

## Models Implemented

### 1. Linear Regression

Used as the baseline regression model.

### 2. Ridge Regression

Applied regularization to reduce overfitting and improve generalization.

### 3. Decision Tree Regressor

Used to capture non-linear relationships within the dataset.

## Evaluation Metrics

The models were evaluated using:

* RMSE (Root Mean Squared Error)
* R² Score

## Results

| Model                   | RMSE     | R² Score |
| ----------------------- | -------- | -------- |
| Linear Regression       | 70060.52 | 0.6254   |
| Ridge Regression        | 70057.42 | 0.6255   |
| Decision Tree Regressor | 69680.88 | 0.6295   |

## Best Model

Decision Tree Regressor achieved the best performance with:

* RMSE: 69680.88
* R² Score: 0.6295

## Visualization

An Actual vs Predicted House Prices scatter plot was generated to visually evaluate model performance.

## Project Structure

AI_ML_Task2_Model_Comparison.ipynb

README.md

Task2_Report.pdf

## Learning Outcomes

Through this project, I learned:

* Data preprocessing techniques
* Feature engineering concepts
* Feature scaling using StandardScaler
* Model training and evaluation
* Performance comparison of machine learning models
* Selecting the best-performing model based on evaluation metrics

## Conclusion

This project demonstrates an end-to-end machine learning workflow involving preprocessing, feature scaling, model optimization, evaluation, and comparison. Among the evaluated models, Decision Tree Regressor achieved the best predictive performance on the California Housing Dataset.
