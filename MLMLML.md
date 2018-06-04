---
layout: default
title: Learning
---
[.](./)

## Machine Learning for newbies
_Note: Explanations, descriptions and pictures taken from [Machine Learning by Prof Andrew Ng](https://www.coursera.org/learn/machine-learning)  unless stated otherwise._

### Supervised Learning: Random Forest and XGBoost 
Found a tutorial on [Machine Learning on Kaggle](https://www.kaggle.com/learn/machine-learning). Replicated the code for the project on Iowa house price prediction [here](https://www.kaggle.com/rayfave/ml-with-random-tree-classifier-xgboost/).

 1. **Sci-kit learn**: 
 A great way to start creating models and predicting outputs. Also learnt to choose predictor parameters (numerical) to be trained with the `DecisionTreeRegressor`.

 1. **Model Validation**: Using `Mean Absolute Error` to evalute model;  Splitting training set into train-validation sets; 
 
 1. **Underfitting, overfitting and optimisation**: Ensuring model performs well by reducing over/underfitting using the `max_leaf_nodes` feature on the `DecisionTreeRegressor`.

 1. **Random Forests**: A slightly more sophisticated machine learning algorithm with better results.
 
 1. **Feature selection and engineering**: Handling `NaN` values via imputation, categorical values via `One Hot Encoding` (ie `pandas.get_dummies`).
 
 1. **XGBoost**: Gradient Boosted Decision Tree algorithm with more tuning required (`learning rate`, `n_estimators`, `early_stopping_rounds` and `n_jobs`) but delivers better prediction.

 *To be continued*

### Unsupervised Learning

*In progress..*

<!-- **Context:** _I have a bunch of users on my app doing a bunch of things.. How can I segment them into meaningful, actionable groups?_

**K-means clustering** 

Using K-means clustering,

**Feature clean up** -->

[back](./)