# PredictFutureSales
Forecast monthly sales per product–store using Kaggle’s Predict Future Sales dataset. Practice real-world skills: time-series forecasting, lag features, feature engineering, categorical handling, large data, and time-based model validation.

PredictFutureSales
This project is based on the Kaggle competition “Predict Future Sales”, which was the final project of the Coursera course: How to Win a Data Science Competition: Learn from Top Kagglers.
The goal is to predict the total monthly sales for each product–store combination using historical sales data.

Project Description
You are given historical daily sales data (time-series) from 1C Company.
The task is to predict the item_cnt_month (number of items sold in the next month) for every:

shop_id
item_id
This project involves real-world forecasting, not just regression or classification.

Why This Project Is Important
This project helps practice real data science skills, including:

Time-series forecasting
Feature engineering
Lag features
Handling categorical variables
Working with large datasets
Avoiding data leakage
Model validation for time-series
Challenges
Huge number of shop–item combinations
Many zero-sales months
Strong seasonality and trends
Data noise
Need for lag-based features
Proper train/validation split (time-based, not random)
Dataset
The dataset is available on Kaggle: Predict Future Sales

Main files:

sales_train.csv – historical daily sales
items.csv – item metadata
shops.csv – shop metadata
item_categories.csv – item categories
test.csv – submission file
Project Workflow
Data Loading and Exploration – Understand dataset structure, missing values, and data types.
Data Preprocessing – Clean data, handle missing values, encode categorical variables.
Feature Engineering – Create lag features, rolling averages, and other time-series features.
Modeling – Train regression or advanced time-series models.
Evaluation – Use time-based validation to avoid data leakage.
Prediction & Submission – Predict item_cnt_month and prepare Kaggle submission.
Results
Monthly sales forecasts for each product–store combination.

Insights on seasonality, trends, and shop/item performance.

Kaggle competition: Predict Future Sales

Coursera course: How to Win a Data Science Competition: Learn from Top Kagglers
