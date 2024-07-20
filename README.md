# CognifyzTechnologies_Internship_tasks
This repository contains the files I worked on during my Machine Learning internship at Cognifyz technologies. The internship was undertaken in Jun-July 2024. They provided me a large dataset of restaurants and my main role for me was to build a model to predict the ratings of restaurants and gather meaningful insights from the data.

# Task 1
Objective: Build a machine learning model to predict the aggregate rating of a restaurant based on other features.

Steps:

Preprocess the dataset by handling missing values, encoding categorical variables, and splitting the data into training and testing sets.
Select a regression algorithm (e.g., linear regression, decision tree regression) and train it on the training data.
Evaluate the model's performance using appropriate regression metrics (e.g., mean squared error, R-squared) on the testing data.
Interpret the model's results and analyze the most influential features affecting restaurant ratings.

# Task 2
Objective: Create a restaurant recommendation system based on user preferences.

Steps:

Preprocess the dataset by handling missing values and encoding categorical variables.
Determine the criteria for restaurant recommendations (e.g., cuisine preference, price range).
Implement a content-based filtering approach where users are recommended restaurants similar to their preferred criteria.
Test the recommendation system by providing sample user preferences and evaluating the quality of recommendations.

# Task 3
Objective: Develop a machine learning model to classify restaurants based on their cuisines.

Steps:

Preprocess the dataset by handling missing values and encoding categorical variables.
Split the data into training and testing sets.
Select a classification algorithm (e.g., logistic regression, random forest) and train it on the training data.
Evaluate the model's performance using appropriate classification metrics (e.g., accuracy, precision, recall) on the testing data.
Analyze the model's performance across different cuisines and identify any challenges or biases.

# Dataset
CSV file is uploaded here in the repo

# Platform
Vs Code

# Libraries
pandas, numpy, matplotlib, seaborn, scikitlearn

# Data Preprocessing and splitting
Cuisines had 9 null values. So dropped
Removed features that will inhibit model performance
The target variables were balanced
Split training data and test data in the ratio 8:2

# Model Evaluation
Random Forest performs better on the model than logistic regression.

