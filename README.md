# Linear Regression Model for House Price Prediction

This Python script implements a linear regression model to predict house prices based on selected features. It uses the 'train.csv' dataset containing information about residential properties.

## Requirements
- Python 3.x
- Required Libraries: `numpy`, `pandas`, `scikit-learn`

## How to Use
1. Ensure you have Python installed on your system.
2. Install the required libraries using pip:
```
pip install numpy pandas scikit-learn
```
3. Download the `train.csv` dataset.
4. Place the dataset file in the same directory as the script.
5. Run the script.

## Description
- The script imports necessary libraries such as `numpy`, `pandas`, and `scikit-learn`.
- It loads the dataset using Pandas.
- Rows with missing values in specific columns (`GrLivArea`, `BedroomAbvGr`, `FullBath`, `SalePrice`) are dropped.
- Features (`GrLivArea`, `BedroomAbvGr`, `FullBath`) and the target variable (`SalePrice`) are selected.
- The data is split into training and testing sets using the `train_test_split` function from scikit-learn.
- A linear regression model is initialized and fitted to the training data.
- Predictions are made on the testing data using the trained model.
- The model is evaluated using the R-squared score.

## Video


https://github.com/Smit-Zaveri/PRODIGY_ML_01/assets/104667864/e316e27f-df3a-422a-8f47-21026244c7d6



## Output
The script prints the R-squared score, which indicates the proportion of the variance in the dependent variable (house prices) that is predictable from the independent variables (selected features). Additionally, it displays a DataFrame containing the actual and predicted house prices for the testing data.

## Author
[Smit Zaveri](https://github.com/Smit-Zaveri/Smit-Zaveri)

## Acknowledgments
- The dataset used in this script is obtained from [\[source link\]](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data).
