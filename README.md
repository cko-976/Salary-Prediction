# Salary-Prediction

# Overview

The work is aimed at predicting salary from Census data by using a classification model. 

The 5-fold cross-validation will be used to access which model produces the best accuracy score.  

## Goals
- The goal is to train a classfication model that performs better than 0.75 accuracy.

We will use 5-fold Cross-Validation to evaluate which model has the best accuracy score. 
We will also be able to test our model by splitting the data into train and test data sets.


## Motivation and Background
This project is interesting because it aims to predict salary by going through the process of Exploratory Data Analysis, Data Cleaning, Feature Engineering, Modelling and Validation. 

This study will be useful for anyone wanting to learn how to make predictions using categorical data.

It is also useful for anyone wanting to learn how to select a model using K-fold Cross-Validation.

Other people have done work on this data set, for example [Ron Kohavi](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf), 1996, "Scaling Up the Accuracy of Naives-Bayes Classifier: A Decsion Tree hybrid", used the adult data to show the usefulness of Naives-Bayes Classifier. 
The data has also been used by in work titled ['adult income predictor'](https://www.youtube.com/watch?v=RdggP4yuIHY) using different classifiers, such as Decision Tree, Gradient Boost Classifier and Logistic Regression.


## Data
The project uses the 1994 Census data from UCI Machine Learning Repository, [UCI ML](https://archive.ics.uci.edu/ml/datasets/Census+Income).  
It has 14 features and 32561 rows. It also referred to as the adult data.
[Data]

## Table of Contents
[Technical Report]

## Packages

  **Libraries:** Numpy, Pandas, Matplotlib, Sklearn, Seaborn
 
- from  Sklearn - LogisticRegression, ColumnTransformer, OneHotEncoder, DecisionTreeClassifier, LabelEncoder, 
CrossValidate, train_test_split, Confusion Matrix.

