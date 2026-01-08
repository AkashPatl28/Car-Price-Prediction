# Car-Price-Prediction
This machine learning project focuses on predicting outcomes using structured data by applying data preprocessing, categorical encoding, and model training techniques. The project demonstrates the complete ML workflow from data cleaning and feature engineering to model building and evaluation using Python and scikit learn.


## Car Price Prediction using Machine Learning

This project aims to predict the selling price of a car based on its features such as model, fuel type, transmission, and other relevant attributes. The goal is to demonstrate a complete machine learning pipeline including data preprocessing, feature encoding, model training, and evaluation.

## Project Workflow

 1. Dataset loading and initial inspection

 2. Data cleaning and removal of duplicate records

 3. Handling missing and inconsistent values

 4. Encoding categorical features using Label Encoding

 5. Feature selection and train test split

 6. Model training using machine learning algorithms

 7. Model evaluation using performance metrics

 8. Final price prediction on unseen data

#$ Features Used

 1. Car model

 2. Fuel type

 3. Transmission type

 4. Manufacturing year

 5. Mileage

 6. Engine capacity

 7. Other numerical and categorical attributes

#$ Machine Learning Techniques

 1. Supervised learning

 2. Regression based modeling(Linear Regression)

 3. Feature engineering

 4. Data preprocessing

## Technologies and Tools

 1. Python

 2. NumPy

 3. Pandas

 4. Scikit learn

 5. Kaggle

## Dataset Description

 The dataset used in this project is ford.csv, which contains detailed information about used Ford cars. It is designed to help build a machine learning model that predicts car prices based on multiple features.

## Dataset Features

 1. The dataset includes the following key attributes:

 2. model: Model name of the Ford car

 3. year: Manufacturing year

 4. price: Selling price of the car (target variable)

 5. transmission: Type of transmission (Manual or Automatic)

 6. mileage: Distance driven by the car

 7. fuelType: Fuel type (Petrol, Diesel, Hybrid, etc.)

 8. tax: Road tax value

 9. mpg: Miles per gallon

 10. engineSize: Engine capacity

## Results

 * Built a Linear Regression model to predict car selling prices using structured car dataset

 * Model performance was evaluated on test data using regression metrics

 * Achieved the following results:

 * Metric	Value
   * R² Score	0.78
   * Adjusted R² Score	0.76

 * The R² score indicates that the model explains a significant portion of variance in car prices

 * Adjusted R² confirms model reliability while accounting for the number of input features

## Future Improvements

 * Compare with advanced regression algorithms (Random Forest, XGBoost)

 * Use cross-validation
