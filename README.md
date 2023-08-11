# Insurance Cost Prediction & Analysis

This repository contains an analysis of predicting insurance costs using machine learning models. The analysis covers data preprocessing, exploratory data analysis, model training using Linear Regression, RandomForestRegressor, and XGBRFRegressor, and building a predictive system based on user input.

## Introduction

The analysis focuses on predicting insurance costs based on various features such as age, BMI, number of children, sex, smoking status, and region. Different machine learning regression models are utilized to achieve accurate cost predictions.


## Data

The dataset used in this analysis is `insurance.csv` , which contains information about individuals' insurance costs and relevant features.

## Analysis Steps

1. **Data Loading and Preprocessing**: The dataset is loaded using pandas. Duplicate values and missing values are addressed.

2. **Exploratory Data Analysis (EDA)**: Basic statistics and visualizations are used to understand the distribution of features like age, BMI, sex, smoking status, region, etc.

3. **Data Preprocessing**: Categorical features are one-hot encoded. The dataset is split into training and testing sets.

4. **Model Training**: Linear Regression, RandomForestRegressor, and XGBRFRegressor models are trained and evaluated on the testing set.

## Results

The analysis provides insights into the relationships between various features and insurance costs. Model performances are assessed using the R-squared score.

## Predictive System

A predictive system is built to estimate insurance costs based on user input for age, BMI, number of children, sex, smoking status, and region. The system utilizes the trained regression models to provide cost predictions.

## Conclusion

The analysis showcases the effectiveness of different regression models in predicting insurance costs. The predictive system can be used to obtain quick estimates of insurance costs based on user information.

