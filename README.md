# 🚗 Car Price Prediction Using Linear Regression

## 📌 Project Overview

This project aims to predict used car selling prices based on vehicle characteristics using **Machine Learning**.

The project includes data cleaning, exploratory data analysis (EDA), feature engineering, data visualization, and building a **Linear Regression** model to estimate car prices.

## 🎯 Project Objectives

- Explore and understand the used car dataset.
- Handle missing values and investigate outliers.
- Analyze relationships between car features and selling prices.
- Prepare numerical and categorical features for modeling.
- Build and evaluate a Linear Regression model.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📊 Dataset Features

The dataset contains information about used cars, including:

- **Year:** Manufacturing year
- **Selling Price:** Target variable
- **KM Driven:** Total distance traveled
- **Fuel:** Fuel type
- **Seller Type:** Type of seller
- **Transmission:** Manual or automatic
- **Owner:** Previous ownership category
- **Mileage:** Fuel efficiency
- **Engine:** Engine capacity
- **Max Power:** Engine power
- **Seats:** Number of seats

## 🔍 Project Workflow

### 1. Data Cleaning and Preprocessing
- Removed unnecessary columns.
- Converted numerical features stored as text into numeric values.
- Handled missing values using median and mode.
- Investigated outliers using boxplots and the IQR method.
- Encoded categorical variables using One-Hot Encoding.

### 2. Exploratory Data Analysis (EDA)
- Analyzed selling price distributions.
- Used scatter plots to examine numerical relationships.
- Used boxplots to compare prices across categorical groups.
- Created a correlation heatmap to identify relationships between features.

### 3. Model Building
- Selected input features and the target variable.
- Split the dataset into 80% training and 20% testing.
- Trained a Linear Regression model.
- Generated predictions on the test dataset.

## 📈 Model Performance

| Evaluation Metric | Result |
|---|---|
| MAE | 172,330.94 |
| RMSE | 310,709.12 |
| R² Score | 0.56 |

The model explains approximately **56% of the variance** in used car selling prices, indicating moderate predictive performance and opportunities for further improvement.

## 🚀 Future Improvements

- Experiment with Random Forest and Gradient Boosting models.
- Improve feature engineering and feature selection.
- Investigate the impact of extreme values.
- Use cross-validation and hyperparameter tuning.
- Explore target transformations to improve predictions.

## 📌 Conclusion

This project demonstrates an end-to-end machine learning workflow for predicting used car prices using Linear Regression.

It provides practical experience in data preprocessing, exploratory data analysis, feature engineering, model training, and performance evaluation.
