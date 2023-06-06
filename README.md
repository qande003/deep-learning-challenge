# deep-learning-challenge
Module 21

# Purpose of the Analysis:
The purpose of this analysis is to use our knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

# Answers to Data Preprocessing Questions:

## Target Variable(s): The target variable is the "IS_SUCCESSFUL" variable.

## Feature Variable(s):
APPLICATION_TYPE
AFFILIATION
CLASSIFICATION
USE_CASE
ORGANIZATION
STATUS
INCOME_AMT
SPECIAL_CONSIDERATION
ASK_AMT
NAME (In Optimization Model only)
Removed Feature(s):
EIN
NAME (In base model. Added it back into optimized model)

# Compiling, Training, and Evaluating the Model
The original and optimized model incorporated three hidden layers. The original model used 80, 30, and 1 neurons in those layers. The optimized model used 512, 256, and 128 neurons for its layers.

Original model:

![image](https://github.com/qande003/deep-learning-challenge/assets/95590929/d24c881d-db57-4210-8c3c-47a43286e45f)

Optimized model:

![image](https://github.com/qande003/deep-learning-challenge/assets/95590929/4e3be2f3-08b6-41a3-9c3f-b58fe7ab72d6)

## I was not able to accomplish and accuracy rate of at least 75% but I did use the following optimization techniques in my attempts:

* Use different activation functions for the hidden layers

* Dropping more or fewer columns

* Add or reduce the number of epochs to the training regimen



