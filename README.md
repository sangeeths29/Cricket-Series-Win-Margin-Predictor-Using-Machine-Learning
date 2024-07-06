# Cricket-Series-Win-Predictor-Using-Machine-Learning
Predicted outcomes of future cricket series using Machine Learning tools

# Overview
In this project, I aim to predict the team which wins future cricket series based upon historical win ratio between various teams. This project was basically completed utilizing data taken from Kaggle and ESPNcricinfo. 

# Tools Used
1. Pandas - Mainly used for data manipulation and analysis
2. Scikit-Learn - Used for implementing and evaluating machine learning algorithms

# Steps Taken
## Step 1 - Future Men's Matches DataFrame Creation
In this step, I took the confirmed future men's matches schedule from ESPNcricinfo and used the Pandas library to convert it into a dataframe followed by converting it into a CSV for using for future predictions.

## Step 2 - Loading the Datasets
I loaded the historical odi, tests and t20 dataset along with future men's matches dataset which was created in the previous step.

## Step 3 - Cleaning Historical Data
In this step, I extracted the numerical values out of the margin columns in each of the historical odi, test and t20 datasets. 

## Step 4 - Calculating win ratios for each match type
Here, I added win ratios column to each historical dataset of odi, test and t20, by first doing the calculations using a function to clean and calculate the win ratio margin.

## Step 5 - Preparing historical data with win ratios and margins
Here, I prepared each of the historical datasets by adding win ratios and margins to the dataset. 

## Step 6 - Training separate regression models for each match type
This step involves creating and evaluating a logistic regression model. Then we train the model.

## Step 7 - Predicting Future Series Outcome
Here, the outcomes of future series matches is predicted for each match type based upon the features used in the previous steps.

![image](https://github.com/sangeeths29/Cricket-Series-Win-Margin-Predictor-Using-Machine-Learning/assets/73825180/b3469261-bc5d-405b-882b-faf48d92e2a4)

