# 2018-Kaggle-Maching-Learning-Data-Science-Survey-Challenge

Kaggle hosted an open data scientist competition titled “2018 Kaggle ML & DS Survey Challenge.” The purpose of this challenge was to “tell a data story about a subset of the data science community represented in this survey, through a combination of both narrative text and data exploration.” More information on the competition, data, and prizes can be found on: https://www.kaggle.com/kaggle/kaggle-survey-2018
The dataset used in this project (Kaggle_Salary.csv) contains a modified version of the survey results provided by Kaggle in the file mutiplechoiceResponses.csv. The survey results from 15429 participants are shown in 395 columns, representing survey questions. Not all questions are answered by each participant, and responses contain various data types.
In the dataset, Q9 “What is your current yearly compensation (approximate $USD)?” has been modified from a range to an integer to be used for regression. This has been done by replacing the compensation range with a random integer from a uniform distribution within that range. Rows with null values or undisclosed salaries have been dropped. The column “Q9” contains the target variable, and an index column “index” has been added.

The purpose of this project is to:

1) Understand and explore employment in the data science community, as represented in a survey conducted by Kaggle.
2) Train, validate, and tune multiple regressors that can predict, given a set of survey responses by a data scientist, what a survey respondent’s current yearly compensation is.
Regression or prediction is a supervised machine learning approach used to predict a value of one variable when given the values of others. Many types of machine learning models can be used for training regressors, such as linear regression, decision trees, kNN, SVM, random forest, gradient-boosted decision trees and neural networks.
