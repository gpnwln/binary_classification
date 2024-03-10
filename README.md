# Binary classification

The machine learning methods used are options for solving the binary classification problem.

## Usage

Open the Profile task.pane file and run the machine learning models sequentially.

## Input Files

   trainee_train.csv is the data that should be used to train models.
   trainee_test_fish.csv - data to predict the value of 'im' for.

## Description of the Solution

During the solution, machine learning models were compared using the ROC-AUC metric.

The following methods were used to solve the problem:
1) Bernoulli algorithm of the naive Bayesian classifier
2) Logistic regression
3) Decision trees
4) SVM classifier
5) Random forest
6) Gradient boosting (Catboost)
7) Neural network (multilayer perceptron)

The best machine learning model for solving the binary classification problem turned out to be the Catboost model
