# Benagaluru House Price Prediction Model

This repository contains code and resources for building a machine learning model to predict house prices in bengaluru based on various features.

## Overview

The goal of this project is to develop a predictive model that can accurately estimate the sale price of houses given a set of input features such as total square feet, location, number of bedrooms, etc. The model will be trained on historical housing data and evaluated on its ability to make accurate predictions on new unseen data.

## Dataset

The dataset used for this project is the bengaluru_house_prices.csv, which contains information about houses including features such as size, number of bedrooms, number of bathrooms, location, and sale price. 

You can download the dataset from [[link to dataset]](https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data).

## Project Structure

The project is organized as follows:

- `bengaluru_house_prices.csv`: This file contains the dataset used for training and testing the model.
- `Bengaluru House Price Prediction.ipynb`: This Jupyter notebook used for data exploration, preprocessing, model training, and evaluation.
- `models`: This directory contains saved model files after training.

## Dependencies

The project requires the following Python libraries:

- numpy
- pandas
- scikit-learn
- matplotlib

## Steps : 
1. Gathering Data
2. Explore and Understand the data
3. Preprocessing the data
4. Feature Engineering
5. Model Selection and training
6. Evaluate Model Performance
7. Export the model

## Samples of Outlier removal
1. Location : Hebbal
   ![Hebbal](https://github.com/Prajwal-1718/Bengaluru_House_Price_Prediction/assets/68771962/cc399504-1452-45e8-81bf-88f0387d390d)

2. Location : Rajaji nagar
   ![Rajaji nagar](https://github.com/Prajwal-1718/Bengaluru_House_Price_Prediction/assets/68771962/a76b2dc1-5feb-4af1-838c-57ba186ae946)

## Results
* Initial score of the model (Linear Regression)
  
  ![MSS](https://github.com/Prajwal-1718/Bengaluru_House_Price_Prediction/assets/68771962/c09b3975-dab8-4fde-9347-1c8e275a3b8d)

* Cross-Validation Score of the Linear Regression
  
  ![CVS](https://github.com/Prajwal-1718/Bengaluru_House_Price_Prediction/assets/68771962/81d60258-7605-4c75-859f-ee07ad4de7e9)

* Finding the BEST model and their parameters using **GridSearchCV()**
  
  ![BM](https://github.com/Prajwal-1718/Bengaluru_House_Price_Prediction/assets/68771962/66526f56-a168-4525-b1c5-18c3c4e1249d)




