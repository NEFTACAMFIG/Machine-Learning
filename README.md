# Machine Learning Repository

## Overview

This repository contains implementations of basic machine learning algorithms for predictive modeling. The primary focus is on regression models and decision trees/random forests applied to real-world datasets.

## Regression Models

In the `Regression_Models.py` file, we apply linear regression and feature regression models using Scikit-Learn to predict life expectancy using the Global Health Observatory (GHO) dataset from the World Health Organization (WHO). The dataset "Life Expectancy" (`life_expectancy.csv`) contains detailed information about various factors affecting life expectancy.

### Exercise Details:

1. **Linear Regression:** 
   - We use Scikit-Learn to implement linear regression to predict life expectancy based on independent variables.
   
2. **Feature Regression:**
   - We explore feature regression techniques to identify the most significant independent variables affecting life expectancy.
   
3. **Backward Elimination:**
   - We perform backward elimination to improve model performance by removing less meaningful independent variables.

## Decision Trees & Random Forest

In the `Decision_Tree_&_Random_Forest.py` file, we use a loan dataset to test decision tree and random forest algorithms for predicting loan approval based on independent variables.

### Exercise Details:

- **Decision Tree & Random Forest:**
  - We utilize decision tree and random forest algorithms to predict whether a person should receive a loan based on independent variables such as income, credit score, and employment status.
