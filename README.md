# Introduction

The goal is to find out if a car model is worthy of a recall. It is a binary classification problem with "recall" referred to as class 1 and "do not recall" as class 0. Data is divided in to 70 % tarining and 30 % validation. The test data is composed of only one row where recall is not known. Some of the variables inside the test data also does not match the training or validation data. Therefore, those variables are replaced by a global constant "-1".

To solve this problem, experimentation with KNN and Decision Tree (DT) shows that KNN has better
performance as compared to DT and that the released model is recommended as recall.

# Usage

Notebook ```car_data.ipynb ```takes input data in the form of a csv file which shows if a particular car is worthy of a recal or not depending on different variables. This data is used for training of two machine learning models and then prediction is made on the test data. 

The hypermeters parameters of both models are tunned and the parameters are provided in the Notebook.
