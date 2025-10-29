Bangalore House Price Prediction uses machine learning to predict house prices in Bangalore based on various features like location, size, and square footage. The project focuses on data preprocessing, feature engineering, and building regression models to make accurate predictions.

Overview This project involves building a regression model to predict house prices in Bangalore using a dataset of 13,320 house listings. Key steps include data cleaning, feature engineering, and applying machine learning models such as Linear Regression.

Objectives: Clean and preprocess the dataset. Engineer relevant features such as BHK (Bedrooms, Hall, Kitchen) and price per square foot. Handle outliers and anomalies in the dataset. Train a regression model to predict house prices.

Dataset: The dataset contains information about house prices in Bangalore and includes the following features:

area_type: Type of area (e.g., Super built-up, Plot Area). availability: When the property is available. location: Location of the property in Bangalore. size: Number of bedrooms. total_sqft: Total square footage of the property. bath: Number of bathrooms. balcony: Number of balconies. price: Price of the property (in lakhs).

Exploratory Data Analysis The initial dataset contains 9 columns and 13,320 rows. We perform exploratory data analysis (EDA) to understand the distribution of house prices and other features.

Key insights:

The dataset includes properties of various sizes and price ranges across different locations in Bangalore. Some properties have missing values or unusual data, which are handled through data cleaning. Feature Engineering We perform several feature engineering steps, including:

Handling NA values: Drop rows with missing values in crucial columns. Converting total_sqft to numeric: Some values are in range format (e.g., "2100 - 2850"). These are converted to their average. BHK (Bedrooms Hall Kitchen): Extract the number of bedrooms from the size column. Price per Square Foot: Calculate price per square foot to compare properties. Model Building We use the following models to predict house prices:

Linear Regression Decision Tree Random Forest After preprocessing and feature engineering, one-hot encoding is applied to the categorical "location" feature to prepare the dataset for modeling.

Results The performance of the models is evaluated using RMSE (Root Mean Square Error). The best-performing model is chosen based on its accuracy and generalization on the test data.
