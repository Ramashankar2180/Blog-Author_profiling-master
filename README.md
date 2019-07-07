# Introduction

To train a machine learning model to classify a blog
author on the basis of the text and the topics in which the author has an interest. To
solve this problem, first we analyzed the data with the help of pandas and numpy
python packages. Then we performed the data cleaning of the data set given.
Various machine learning algorithms such as Random Forest classifier, SVM,
Bernoulli Naive Bayes, Multilayer perceptron. We measured the performance of
these models and in future I will try to improve the performance of the model.

Dataset
For this practice problem, we have been given three CSV files: train, test and sample submission.

Train file will be used for training the model, i.e. our model will learn from this file. It contains all the independent variables and the target variable.
Test file contains all the independent variables, but not the target variable. We will apply the model to predict the target variable for the test data.
Steps that I followed :
Firstly I import the test.csv and train.csv using pandas.read_csv()

Performed EDA Data Preprocessing i.e. missing data removal, onehotencoding

Then i applied different machine learning models:

Tool:
Jupyter
