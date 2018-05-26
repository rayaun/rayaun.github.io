---
layout: default
title: Learning
---
[.](./)

## Machine Learning for newbies
_Note: Explanations, descriptions and pictures taken from [Machine Learning by Prof Andrew Ng](https://www.coursera.org/learn/machine-learning)  unless stated otherwise._

### What is Machine Learning?

### Random Forest and XGBoost model on tutorial
Found a tutorial on [Machine Learning on Kaggle](https://www.kaggle.com/learn/machine-learning). Replicated the code for the project on Iowa house price prediction [here](https://www.kaggle.com/rayfave/ml-with-random-tree-classifier-xgboost/).

**What have I learnt so far?**
 1. **Sci-kit learn**: 
 A great way to start creating models and predicting outputs. Also learnt to choose predictor parameters (numerical) to be trained with the `DecisionTreeRegressor`.
 2. Model Validation, underfitting, overfitting and optimisation: Using the `Mean Absolute Error` to evalute model;  Splitting training set into train-validation sets; Ensuring model performs well by reducing over/underfitting using the `max_leaf_nodes` feature on the `DecisionTreeRegressor`.
 3. Random Forests: A slightly more sophisticated machine learning algorithm with better results.
 5. Feature selection: Handling `NaN` values via imputation, categorical values via `One Hot Encoding` (ie `pandas.get_dummies`).
 4. XGBoost: Gradient Boosted Random Forest algorithm with more tuning required (learning rate, )

<!-- ### Unsupervised Learning

**Context:** _I have a bunch of users on my app doing a bunch of things.. How can I segment them into meaningful, actionable groups?_

**K-means clustering** 

Using K-means clustering,

**Feature clean up** -->

[back](./)