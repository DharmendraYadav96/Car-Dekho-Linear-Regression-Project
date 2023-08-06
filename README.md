# Car-Dekho-Linear-Regression-Project

This repository contains the data science project for performing linear regression on the Car Dekho dataset. The goal of this project is to predict the selling price of a car based on the given data attributes.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)
- [Contributing](#contributing)


## Introduction

The car resale market is an essential aspect of the automotive industry. The Car Dekho Linear Regression project aims to build a predictive model to estimate the selling price of used cars based on various features like car age, mileage, fuel type, and other relevant factors. By creating such a model, it can help car sellers and buyers understand the approximate value of the car and make informed decisions.

## Dataset

The dataset used in this project is the "CAR DETAILS FROM CAR DEKHO.csv" dataset, which includes various attributes of used cars along with their selling prices. The dataset is stored in the `data` directory and is provided in CSV format. It contains the following columns:

- name: The name of the car model.
- year: The manufacturing year of the car.
- selling_price: The selling price of the car (Numerical).
- km_driven: The total distance the car has been driven (Numerical).
- fuel: The type of fuel used by the car (Categorical).
- seller_type: The type of seller (Categorical).
- transmission: The type of transmission (Categorical).
- owner: The number of previous owners of the car (Categorical).

## Usage

The project is implemented using Jupyter Notebook. The main notebook file is `car_dekho_linear_regression.ipynb`. It contains the entire data preprocessing, model training, and evaluation pipeline. Each step is well-documented and includes explanations of the decisions taken during the process.

Simply run the notebook cell by cell to see the step-by-step execution of the project. You can modify the notebook according to your needs, experiment with different models, and tune hyperparameters for better performance.

## Methodology

The project follows these key steps:

1. Data Exploration: Analyzing the dataset to understand its structure and identifying any missing or irrelevant data.

2. Data Wrangling: Cleaning the data by handling missing values, Extracting relevant features, Handling outliers.

3. Exploratory data Analysis:  Examined the data for skewness, normal distribution, and outliers in numerical features. We also analyze the correlation between these features and the target variable (selling price). Additionally, we visualize the relationships using scatter plots, histograms, and box plots. 

4. Feature Engineering: Converting categorical variables to numerical, and scaling numeric features if necessary.

5. Model Training: Training the selected model on the preprocessed dataset.

6. Model Evaluation: Assessing the model's performance on a test dataset and interpreting the results.

7. Prediction: Making predictions on new data based on the trained model.

## Results

The project aims to achieve an accurate prediction of the selling price of used cars. The model's performance can be evaluated using various metrics such as Root Mean Squared Error (RMSE), R-squared, and Mean Absolute Error (MAE). The results and findings are discussed in the notebook.

## Contributing

Contributions to this project are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request. For major changes, please discuss your ideas in the issues section before making any modifications.

---
Happy predicting! 🚗💨
