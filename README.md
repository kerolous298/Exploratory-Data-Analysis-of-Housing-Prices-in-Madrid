# 🏠 Exploratory-Data-Analysis-of-Housing-Prices-in-Madrid


## 📌 Project Overview

This project analyzes housing data from Madrid to understand the factors influencing house prices and build a predictive model. It involves data cleaning, exploratory data analysis (EDA), and the development of linear regression models.

## 🗂️ Data Source

### 1. `houses_Madrid.csv`  
- The original dataset containing housing listings in Madrid.
- Columns include: `price`, `size`, `rooms`, `location`, etc.

### 2. `Madrid_cleaned_data.csv`  
- Cleaned version of the dataset after processing nulls, inconsistencies, and formatting issues.
## Methodology

1. **Data Loading and Cleaning:** The project starts by loading the data into a Pandas DataFrame and performing necessary data cleaning steps, such as converting data types.
2. **Exploratory Data Analysis (EDA):** Univariate and bivariate analyses are conducted to understand the distributions of variables and their relationships. This includes:
    - Histograms and box plots to visualize the distribution of numerical features like buy price, area, number of rooms, and bathrooms.
    - Bar plots to show the distribution of districts in Madrid.
    - Scatter plots and regression plots to examine the correlation between variables, such as area and buy price.
    - Heatmaps to visualize the correlation matrix.
3. **Linear Regression Modeling:** Linear regression models are built to predict house prices based on different features. This includes:
    - Simple linear regression using area as a predictor.
    - Multiple linear regression with area and number of bathrooms as predictors.
    - Multiple linear regression with number of rooms and bathrooms as predictors.
4. **Dummy Variables:** Dummy variables are created for categorical features, such as district, to incorporate them into the regression models.

## Results and Insights

The analysis reveals insights into the housing market in Madrid, such as the most expensive districts and the relationship between property features and prices. The linear regression models provide predictive capabilities for estimating house prices based on given features.

## Usage

To run this project, follow these steps:

1. Make sure you have the necessary libraries installed, including pandas, numpy, plotly, matplotlib, seaborn, and statsmodels. Install them using `pip install <library_name>`. For example, to install pandas, use `pip install pandas`.
2. Upload the "Madrid_cleaned_data.csv" dataset to your Colab environment.
3. Execute the code cells in the provided notebook sequentially.

## Contributing

Feel free to contribute to this project by suggesting improvements, adding new features, or providing feedback.

