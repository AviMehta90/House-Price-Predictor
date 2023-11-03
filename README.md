# House Price Predictor

This GitHub repository contains a project for predicting house prices using various regression techniques and elastic net, including Linear Regression and Ridge Regression. The project aims to demonstrate how different regression methods can be used to predict house prices based on various features of the properties.

## Project Overview

In this project, we explore a dataset of house prices with features such as area, garage, fireplace, number of baths, marble types, floors, city, solar panels, electric connection, fiber optics, glass doors, swimming pool, and garden. Our goal is to build and compare predictive models to estimate house prices accurately.

## Dataset

The dataset used in this project can be found in the `HousePrices_HalfMil.csv` file. It contains 500,000 rows and 15 columns. The columns represent various features of the houses, and the target variable is the "Prices" column.

## Tools and Libraries

The project uses Python and several libraries, including:
- Pandas for data manipulation and analysis
- Numpy for numerical operations
- Matplotlib for data visualization
- Scikit-Learn for machine learning tasks

## Project Structure

The project is organized as follows:
- **Data Preparation**: We start by loading and exploring the dataset. We perform data preprocessing and split the data into training and testing sets.

- **Linear Regression**: We build a Linear Regression model to predict house prices and evaluate its performance on the training and testing data.

- **Ridge Regression**: We implement Ridge Regression with different alpha values and compare the results. Ridge Regression is a form of regularization to prevent overfitting.

- **Lasso Regression**: We also explore Lasso Regression, another form of regularization, to assess its impact on the model's performance.

- **Visualization**: The project includes visualizations that show the impact of different alpha values on the coefficients of the Ridge and Lasso models.

## Results

The project provides insights into how different regression techniques can be applied to predict house prices. We evaluate the performance of each model and compare their results. Additionally, we visualize the coefficient changes when applying regularization techniques.

## Usage

To run this project, you need Python and the required libraries installed. You can follow the Jupyter Notebook provided in this repository for step-by-step execution.

```bash
jupyter notebook House_Price_Prediction.ipynb
```

Feel free to contribute to this project or provide feedback. If you find it helpful, give it a star!
