# Stock-Price-Prediction
Project Description:

This project aims to analyze historical stock prices of Apple Inc. (AAPL) and predict future stock prices using machine learning techniques. The dataset contains daily stock price data including Open, High, Low, Close, Adjusted Close prices, and Volume. The project involves data preprocessing, exploratory data analysis (EDA), principal component analysis (PCA), building and evaluating regression models for stock price prediction, and comparing the performance of different models.

Methods:

Data Preprocessing:

Load the dataset from a CSV file.
Convert the 'Date' column to datetime format.
Check for missing values and remove rows with missing values.
Exploratory Data Analysis (EDA):

Visualize stock prices over time.
Plot correlation heatmap and pairplot for feature analysis.
Principal Component Analysis (PCA):

Separate features and target variable.
Standardize the features.
Apply PCA to reduce dimensionality and visualize the principal components.
Stock Prediction using Moving Average:

Calculate moving averages for stock prices to identify trends.
Building Regression Models:

Split the dataset into training and testing sets.
Train a linear regression model.
Evaluate model performance using mean squared error (MSE).
Implementing a Second Model:

Build and train another linear regression model.
Evaluate the second model's performance.
Advanced Machine Learning Model: Gradient Boosting Regressor

Train a Gradient Boosting Regressor model.
Predict stock prices using the Gradient Boosting Regressor model.
Evaluate the model's performance using mean squared error (MSE).
Results:

Mean Squared Error (Model 1): [MSE_value_1]
Mean Squared Error (Model 2): [MSE_value_2]
Mean Squared Error (Gradient Boosting): [MSE_value_gb]
Additional Visualizations:

Distribution of Stock Prices
Actual vs Predicted Stock Prices (Gradient Boosting)
Note:
Ensure the dataset 'AAPL.csv' is located at the specified file path before running the code. Adjust file paths as necessary for proper execution.
