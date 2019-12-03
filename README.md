# Lending Club Loan Data Case Study

A three part analysis including exploratory data analysis, business analysis and modeling using the Kaggle Lending Club Loan Data in Python.

## Table of Contents
Part 0a: Lending Club Loan Data
Part 0b: Function Definition
Part 1: Data Exploration and Evalaution
Part 2: Business Analysis
Part 3: Modeling

## Part 0
Explain the dataset using additional resources and define functions used through the analysis.

## Part 1
Evaluate the dataset, existing trends in features and necessary pre-processing. This is performed using feature distributions (through histograms and barcharts), feature correlation (primarily pearson), and heatmaps for cleaning. 

## Part 2
Further pre-processing is required for analytics around the cohorts (defined by loan grade and year) existing in the dataset. This includes string parsing and linear regressions for measuring relationships between variables. Aggregated metrics are calculated and bucketized to evaluate cohort performance. This also helps us to draw conclusions on the how risk is associated to return and how it differs per cohort characteristic.

## Part 3
In order to make estimates of our efficacy in predicting if a loan will default, features available at origination are extracted and treated with one-hot encoding if text features. After creating training and evaluation datasets, a logisitc regression model is fit and evaluated using a confusion matrix, precision/recall, F1 score and RMSE. Further steps required to better understand and improve the model are laid out. 

## Credits
Authored by Madison Hawkinson
