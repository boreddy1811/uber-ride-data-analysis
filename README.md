# Uber Rides Data Analysis

This repository contains a Jupyter notebook for analyzing Uber ride data. The analysis includes data cleaning, exploration, and visualization to gain insights into ride patterns and trends.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Findings](#Findings)

## Introduction

The Uber Rides Data Analysis project aims to analyze Uber ride data to identify patterns and trends in ride usage. The analysis includes cleaning the data, filling missing values, and visualizing various aspects of the data.

## Dataset

The dataset used in this analysis includes information about Uber rides such as ride purpose, distance, date and time, and more. The data is cleaned and processed to fill missing values and prepare it for analysis.it is taken from [https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma](https://www.kaggle.com/datasets/brllrb/uber-and-lyft-dataset-boston-ma)

## Findings

- Check how long do people travel with Uber?
- What Hour Do Most People take Uber To Their Destination?
- Check The purpose of trips
- Which Day has the highest number of trips
- What are the number of trips per each day?
- What are the trips in the month?
- The starting points of trips. Where do people start boarding their trip from Most?

## Linear Regression: 
Linear Regression is a supervised machine learning algorithm where the predicted output is continuous and has a constant slope. It’s used to predict values within a continuous range.

## Decision Tree: 
A decision tree is a graphical representation of all the possible solutions to a decision based on certain conditions.

## Random Forest: 
Random Forest is a popular machine learning algorithm that belongs to the supervised learning technique. It can be used for both Classification and Regression problems in ML. It is based on the concept of ensemble learning, which is a process of combining multiple classifiers to solve a complex problem and to improve the performance of the model.

## Gradient Boosting Regressor:
Gradient boosting is a machine learning technique for regression and classification problems, which produces a prediction model in the form of an ensemble of weak prediction models, typically decision trees. It builds the model in a stage-wise fashion like other boosting methods do, and it generalizes them by allowing optimization of an arbitrary differentiable loss function.

## After applying different models on final dataset, we found different accuracy as given below 

| Serial No. | Models                | Accuracy |
|------------|-----------------------|----------|
| 1          | Linear Regression     | 0.747545 |
| 2          | Decision Tree         | 0.961791 |
| 3          | Random Forest         | 0.962269 |
| 4          | Gradient Boosting Regressor | 0.963187 |





