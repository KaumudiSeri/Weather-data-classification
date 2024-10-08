# Weather Data Classification: Determining Humidity
<br>

## Project Overview
<br>
The goal of this project is to build a machine learning classification model to predict the humidity level at 3 PM using data from 9 AM. By leveraging a weather dataset, we aim to preprocess the data, classify humidity values, and then train a model to predict the future humidity level based on earlier data. The model's performance will be evaluated using accuracy as the primary metric.

<br>

## Problem Statement
<br>
In this project, we focus on classifying the relative humidity at 3 PM based on weather data collected earlier in the day. Specifically, we will:

* Predict whether the humidity level at 3 PM will be below or above 25%.
* Use weather data recorded at 9 AM to make these predictions.
* Evaluate the model's performance using classification accuracy.
<br>

## Dataset
<br>
The dataset used for this project is daily_weather.csv, which contains various weather-related features including:

* Temperature
* Humidity
* Wind Speed
* Precipitation
* Cloud Cover
* Atmospheric Pressure
* The column of interest is the relative humidity at 3 PM.
<br>

## Approach
<br>
1. Data Loading:
   
* Download the daily_weather dataset and load it into the Python environment (e.g., Jupyter Notebook).
<br>
2. Data Exploration:
  
* Store the dataset as a Pandas DataFrame.
* Check data statistics, including central tendencies and dispersion.
<br>
3. Data Preprocessing:
  
* Handle missing and null values.
* Address outliers to ensure model robustness.
<br>
4. Classification Setup:

* Convert the relative humidity at 3 PM into binary classes:
    * 0 if the humidity is below 25%.
    * 1 if the humidity is above 25%.
<br>
5. Feature Selection:

* Select relevant features for prediction.
* Split the dataset into X (features) and Y (target humidity class).
<br>
6. Model Building:

* Split the data into training and test sets.
* Train a Decision Tree Classification Model on the training data.
<br>
7. Prediction:

* Use the test set to predict future humidity levels based on the 9 AM data.
<br>
8. Model Evaluation:

* Compare predicted values (Y_pred) against the actual test set values (Y_test).
* Calculate the accuracy score to evaluate model performance.
<br>

## Tools & Technologies

* Programming Language: Python 3.x
* Environment: Jupyter Notebook or any other Python-based IDE
* Libraries:
     * pandas for data manipulation.
     * numpy for numerical operations.
* scikit-learn for machine learning model training and evaluation.
* matplotlib/seaborn for data visualization.
<br>

## Expected Output

* Build a machine learning classification model that predicts the relative humidity at 3 PM using data from 9 AM.
* Measure the model's accuracy based on its prediction of humidity levels in the test set.
<br>

## Conclusion
<br>
This project demonstrates the process of building a machine learning classification model for humidity prediction.