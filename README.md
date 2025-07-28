Project Overview
This project uses linear regression to analyze an e-commerce dataset (from Kaggle: "focusing-on-mobile-app-or-website"). The goal is to predict customer spending based on factors like time spent on the mobile app and website.

Key Steps in the Notebook
Dataset Loading
Dataset fetched from Kaggle using kagglehub.
Data stored in Ecommerce Customers.
Exploratory Data Analysis (EDA)
pandas used to load and inspect data (head(), info()).
Visualizations with seaborn and matplotlib to explore relationships (e.g., time spent on app vs. spending).

Feature Selection & Model Building
Split data into features (X) and target (Y).
Train-test split using train_test_split.
Linear Regression model trained with sklearn.linear_model.LinearRegression().

Model Evaluation
Predictions generated on the test set.
Evaluation metrics:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Residual analysis: histogram and Q-Q plot to check normality.

Insights
The model predicts customer yearly spending based on engagement metrics.
Residuals appear to be normally distributed (good for linear regression assumptions).
The scatter plot of predictions vs. actual values indicates decent fit.
