# Boston Housing Dataset Analysis

This repository contains a machine learning project that analyzes the Boston Housing dataset. The project includes data exploration, preprocessing, model training, evaluation, and visualization.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Data](#data)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Cleaning](#data-cleaning)
- [Feature Scaling](#feature-scaling)
- [Data Splitting](#data-splitting)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Visualization](#visualization)

## Overview

The Boston Housing dataset is a widely-used dataset in machine learning and contains various features related to housing prices in different areas of Boston. The goal of this project is to build a regression model to predict housing prices based on the provided features.

## Installation

To run this project, you need to have Python and the following libraries installed:

- pandas
- numpy
- matplotlib
- scikit-learn
- seaborn

Clone this repository to your local machine using the following command:

```
git clone https://github.com/your-username/boston-housing-analysis.git
```

## Data

The dataset used in this project is the Boston Housing dataset, which is available in the file `boston-housing-dataset.csv`. The dataset contains information about various features such as crime rate, average number of rooms, pupil-teacher ratio, and more.

## Exploratory Data Analysis

The exploratory data analysis (EDA) phase involves understanding the dataset and exploring its characteristics. The EDA process includes examining the dataset's structure, summary statistics, and visualizations.

## Data Cleaning

Data cleaning is an important step to handle missing values, outliers, or any inconsistencies in the dataset. In this project, the column 'MEDV_category' was dropped as it was not required for the analysis.

## Feature Scaling

Feature scaling is performed to standardize the numerical features in the dataset. The StandardScaler from scikit-learn is used to scale the numerical columns to have zero mean and unit variance.

## Data Splitting

The dataset is split into a training set and a test set using the train_test_split function from scikit-learn. The training set contains 80% of the data, and the test set contains the remaining 20%.

## Model Training

In this project, a Linear Regression model is used to predict housing prices. The model is trained using the training set, where the features (X_train) and the target variable (y_train) are separated.

## Model Evaluation

The trained model is evaluated using the mean squared error (MSE), root mean squared error (RMSE), and R-squared (R2) score. These evaluation metrics provide insights into the model's performance on both the training set and the test set.

## Visualization

A scatter plot is created to visualize the predicted housing prices compared to the actual housing prices. The plot helps to understand the relationship between the predicted and actual values.

For more details, refer to the code and comments in the [boston-housing-analysis.ipynb](boston-housing-analysis.ipynb) notebook.

**Note:** The evaluation metrics and visualization in this README are based on a specific run of the project and may vary with different runs or dataset splits.

## Acknowledgments

The Boston Housing dataset used in this project is sourced from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/housing).
