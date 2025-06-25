# Portfolio 1 - Car Price Prediction

## Introduction
This repository contains the code and analysis for predicting the selling price of used cars. The task involves exploring a dataset of car sales and using machine learning algorithms to predict car prices based on several features like year, fuel type, transmission, and seller type.

## Data
The dataset used for this project consists of records from car sales, containing the following key features:
- **Selling Price**: The price at which the car was sold.
- **Year**: The year the car was manufactured.
- **Fuel Type**: The fuel type of the car (Petrol, Diesel, etc.).
- **Transmission**: Whether the car is automatic or manual.
- **Owner**: The number of previous owners the car has had.
- **Seller Type**: Whether the seller is a dealer or an individual.

The dataset was cleaned and processed to remove outliers and handle missing values, ensuring higher model performance.

## Algorithms Applied
1. **Linear Regression**: The primary algorithm used in this portfolio to model the relationship between the car features and the selling price.
2. **Data Cleaning**: Outliers were identified and removed based on a set of predefined rules related to the owner, fuel type, and seller type.
3. **Model Performance Metrics**: The Root Mean Squared Error (RMSE) was used to evaluate the accuracy of the model’s predictions.

## How to Run the Files
1. **Dependencies**: Ensure that Python is installed along with the necessary libraries:
   ```bash
   pip install pandas numpy scikit-learn matplotlib
