# Predict Future Sales

This project is based on the Kaggle competition **“Predict Future Sales”**, which was the final project of the Coursera course [*How to Win a Data Science Competition: Learn from Top Kagglers*](https://www.coursera.org/learn/competitive-data-science).

The goal is to **predict the total monthly sales** for each product–store combination using historical sales data.

---

## Project Description

You are given historical daily sales data from **1C Company**. The task is to predict the `item_cnt_month` (number of items sold in the next month) for every combination of:

- `shop_id`
- `item_id`

This project involves **real-world forecasting**, not just regression or classification.

---

## Why This Project Is Important

This project helps practice key data science skills, including:

- Time-series forecasting
- Feature engineering
- Creating lag features
- Handling categorical variables
- Working with large datasets
- Avoiding data leakage
- Model validation for time-series data

---

## Challenges

- Large number of shop–item combinations
- Many zero-sales months
- Strong seasonality and trends
- Data noise
- Need for lag-based features
- Proper train/validation split (time-based, not random)

---

## Dataset

The dataset is available on Kaggle: [Predict Future Sales](https://www.kaggle.com/c/competitive-data-science-predict-future-sales)

**Main files:**

- `sales_train.csv` – Historical daily sales data
- `items.csv` – Item metadata
- `shops.csv` – Shop metadata
- `item_categories.csv` – Item categories
- `test.csv` – Submission file

---

## Project Workflow

1. **Data Loading and Exploration** – Understand dataset structure, missing values, and data types.
2. **Data Preprocessing** – Clean data, handle missing values, encode categorical variables.
3. **Feature Engineering** – Create lag features, rolling averages, and other time-series features.
4. **Modeling** – Train regression or advanced time-series models.
5. **Evaluation** – Use time-based validation to avoid data leakage.
6. **Prediction & Submission** – Predict `item_cnt_month` and prepare Kaggle submission.

---

## Results

- Monthly sales forecasts for each product–store combination.
- Insights on seasonality, trends, and shop/item performance.

---

## References

- Kaggle competition: [Predict Future Sales](https://www.kaggle.com/c/competitive-data-science-predict-future-sales)
- Coursera course: [How to Win a Data Science Competition: Learn from Top Kagglers](https://www.coursera.org/learn/competitive-data-science)

