## Linear Regression Training Project: E-commerce Clients
This project aims to help an e-commerce company decide whether to focus its development efforts on its mobile app experience or its website. We'll achieve this by analyzing customer data using linear regression to understand the factors influencing annual spending.

## Project Objective
The primary objective of this project is to determine whether the company should prioritize improving its mobile app or its website to maximize customer spending. By building a linear regression models, we will identify the relationship between various customer engagement metrics and their total annual spend, providing a data-driven recommendation.

## Data Overview
We'll be working with a simulated [dataset](https://www.kaggle.com/datasets/kolawale/focusing-on-mobile-app-or-website/data) from Kaggle. This dataset contains information about e-commerce customers and includes the following key features:

Avg. Session Length: The average duration (in minutes) of in-store style advice sessions attended by customers.

Time on App: The average time (in minutes) customers spend using the company's mobile application.

Time on Website: The average time (in minutes) customers spend browsing the company's website.

Length of Membership: The total number of years a customer has been a member of the e-commerce platform.

## Models Used
Linear Regression (For the App Data & Website Data)

Elastic Net Regression (before & after hyperparameter tuning, for App and Website data)

Support Vector Regression (SVR) (before & after tuning, for App and Website data)

XGBoost (before & after tuning, trained on all features: membership length, app time, website time)
Model Performance:

## Best Models
Linear Regression was the top-performing model on the app-focused dataset. It achieved the highest R² score (0.8614) and the lowest Mean Absolute Error (MAE) of 22.43, indicating strong predictive accuracy with the benefit of simplicity.

Best Website Model: The tuned Support Vector Regression (SVR) model performed slightly better on the website-focused dataset, with an R² score of 0.6355. However, all models trained on website data showed a much weaker correlation to yearly spending than the app-based models.
