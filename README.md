# PySpark-Regression-Analysis-Predicting-Yearly-Amount-Spent-on-Ecommerce-Customers-Dataset



## Overview
This uses PySpark to perform regression analysis on the Ecommerce Customers dataset. The goal is to predict the yearly amount spent by customers based on various features such as session length, time on app, time on website, and length of membership.

## Dataset
The dataset includes information about customers, including email, address, avatar, average session length, time on app, time on website, length of membership, and yearly amount spent.

### Data Exploration
- Total number of records: 500
- Features: Email, Address, Avatar, Avg Session Length, Time on App, Time on Website, Length of Membership, Yearly Amount Spent

## Machine Learning Workflow
   - Data Loading
   - Data Cleaning and Preparation
   - Data Visualizations
   - Feature selection and transformation.
   - Scaling numerical features.
   - Label encoding categorical features.
   - Regression models used: Linear Regression, GBTRegressor.
   - Training and evaluating each model.
   - Evaluation metrics: Root Mean Squared Error (RMSE), R2 Score.
   - Showcase predictions on a subset of the dataset using visualization.

## Results
- Linear Regression:
   - RMSE: 24.97
   - R2 Score: 87.56%

- GBTRegressor:
   - RMSE: 37.67
   - R2 Score: 71.70%

## Conclusion
The Linear Regression model outperforms the GBTRegressor in predicting yearly amount spent by customers on the Ecommerce platform.

