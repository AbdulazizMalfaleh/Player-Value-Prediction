# Player Value Prediction

This repository contains code and data for predicting the value of football players based on various features. The project involves data exploration, preprocessing, and building multiple machine learning models to predict player values for different positions.

## Table of Contents

- [Introduction](#introduction)
- [Data](#data)
- [Notebooks](#notebooks)
- [Model Building Process](#model-building-process)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to predict the value of football players based on their attributes. Different factors affect the value of players in various positions, and filtering the data does not affect the correlation between the columns. Therefore, we build separate models for different positions to achieve higher accuracy.

## Data

The dataset used in this project is provided in `final_data.csv`. It contains various features relevant to player valuation, such as:

- Player Name
- Age
- Nationality
- Overall Rating
- Potential Rating
- Club
- Value
- Wage
- International Reputation
- Skill Moves
- Position
- Other performance-related metrics

## Notebooks

The repository includes several Jupyter Notebooks for different stages of the project:

- **EDA explain template.ipynb**: Exploratory Data Analysis and initial data preprocessing.
- **svm.ipynb**: Support Vector Machine model building and evaluation.
- **logistic_regression.ipynb**: Logistic Regression model building and evaluation.
- **KNN-modle.ipynb**: K-Nearest Neighbors model building and evaluation.
- **decision_tree.ipynb**: Decision Tree model building and evaluation.

## Model Building Process

### 1. Exploratory Data Analysis (EDA)
In the `EDA explain template.ipynb` notebook, we explore the dataset to understand the distribution of various features, check for missing values, and identify outliers. We also visualize the data to gain insights into how different features correlate with the player's value.

### 2. Data Preprocessing
We preprocess the data by handling missing values, encoding categorical variables, and normalizing numerical features. We also filter outliers to improve the model's performance.

### 3. Feature Engineering
We engineer new features that might help improve the model's accuracy. These features are derived from existing ones and provide additional information about the players.

### 4. Model Training and Evaluation
We train different machine learning models on the preprocessed data for each player position (Goalkeepers, Defenders, Midfielders, Forwards). The models include:
- Support Vector Machine (SVM)
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree

We evaluate each model's performance using metrics such as accuracy, precision, recall, F1-score, and Root Mean Squared Error (RMSE).

