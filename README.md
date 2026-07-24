# Diabetes Dataset Regression Analysis
## Project Overview

The objective of this project is to implement and compare various regression techniques on the Diabetes dataset from sklearn.datasets. The main objective was to predict diabetes disease progression using various machine learning regression models and analyze their performance.

The implemented models included:

. Simple Linear Regression
. Multiple Linear Regression
. Polynomial Regression
. Ridge Regression
. Lasso Regression

The metrics used to evaluate model performance were MAE, MSE, RMSE and R² Score.

## Dataset Description

The Diabetes dataset contains medical measurements collected from patients to predict disease progression after one year.

## Dataset Features

The dataset contains 10 input features:

. Age
. Sex
. Body Mass Index (BMI)
. Blood Pressure (BP)
. Six blood serum measurements (s1-s6)

## Target Variable
. Disease progression value after one year

The dataset contains:

. 442 samples
. 10 independent features
. 1 target variable

## Objectives

The main objectives of this project were:

. Load and analyze the Diabetes dataset.
. Explore feature relationships using statistical analysis and visualization.
. Implement different regression techniques.
. Apply regularization methods to reduce overfitting.
. Compare model performance using evaluation metrics.
. Analyze insights gained from the dataset.

## Technologies Used
. Python
. Jupyter Notebook
. NumPy
. Pandas
. Matplotlib
. Seaborn
. Scikit-learn

## Project Workflow
### Step 1: Data Preparation
. Loaded the Diabetes dataset.
. Converted the dataset into a structured dataframe.
. Checked dataset information and statistical summary.
. Verified missing values.
. Analyzed feature relationships using a correlation heatmap.

### Step 2: Simple Linear Regression
. Selected BMI as the independent feature.
. Used disease progression as the target variable.
. Split data into training and testing sets.
. Trained a Linear Regression model.
. Evaluated performance using MAE, MSE, RMSE, and R² Score.
. Visualized actual and predicted values.

### Step 3: Multiple Linear Regression
. Used all available features for prediction.
. Trained a multiple regression model.
. Compared actual and predicted values.
. Evaluated model performance using regression metrics.

### Step 4: Polynomial Regression
. Applied polynomial feature transformation.
. Tested different polynomial degrees.
. Observed the effect of increasing model complexity.
. Analyzed underfitting and overfitting behavior.

### Step 5: Ridge and Lasso Regression
#### Ridge Regression
. Applied L2 regularization.
. Tested different alpha values.
. Reduced large coefficient values to improve model stability.
#### Lasso Regression
. Applied L1 regularization.
. Performed feature selection by reducing less important coefficients.
. Compared performance with Ridge Regression.

### Step 6: Model Comparison and Analysis

All regression models were compared based on:

. Mean Absolute Error (MAE)
. Root Mean Squared Error (RMSE)
. R² Score

Performance visualization was created using bar charts to identify the best-performing model.


## Key Findings
. Multiple features provided better prediction results compared to using a single feature.
. BMI showed a strong relationship with diabetes progression.
. Polynomial Regression increased model complexity but had a risk of overfitting.
. Ridge and Lasso improved model stability through regularization.
. Lasso Regression achieved the best overall performance among tested models.

## Challenges Faced
. Selecting important features from multiple health measurements.
. Understanding relationships between independent variables.
. Managing polynomial model complexity to avoid overfitting.
. Selecting suitable alpha values for Ridge and Lasso models.
. Comparing different regression models using multiple evaluation metrics.

