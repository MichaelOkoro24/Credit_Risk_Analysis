# Credit_Risk_Analysis

## Overview of Analysis:
In this analysis we will be helping Fast Lending use machine learning to help predict credit risk.We built and evaluated several machine learning models and algorithms to predict credit risk. Using techniques such as resampling and boosting to make the most out of the data.

## Results:

## Naive Random Oversampling
![Screen Shot 2022-10-09 at 11 40 34 PM](https://user-images.githubusercontent.com/106411743/194796423-33e827aa-ba8f-4647-abc0-ea927986c880.png)

Balanced Accuracy: 0.646602844334948

Precision: The precision is low for High-risk loans and is high for Low-risk loans.

Recall: High/Low risk = .74/.55


## SMOTE Oversampling
![Screen Shot 2022-10-09 at 11 40 53 PM](https://user-images.githubusercontent.com/106411743/194796443-7d4f9ef8-006c-4719-9c25-8705937892ce.png)

Balanced Accuracy: 0.662394124702461

Precision: The precision is low for High-risk loans and is high for Low-risk loans.

Recall: High/Low risk = .63/.69

## Undersampling
![Screen Shot 2022-10-09 at 11 41 17 PM](https://user-images.githubusercontent.com/106411743/194796485-dec7a806-b961-48d7-bd8d-79254a1bd8cf.png)

Balanced Accuracy: 0.5442166848817717

Precision: The precision is low for High-risk loans and is high for Low-risk loans.

Recall: High/Low risk = .67/.42

## Combination Under-Over Sampling
![Screen Shot 2022-10-09 at 11 41 43 PM](https://user-images.githubusercontent.com/106411743/194796550-ff5b2da1-acdc-4a71-9b45-570278c593c1.png)

Balanced Accuracy: 0.6400726134353378

Precision: The precision is low for High-risk loans and is high for Low-risk loans.

Recall: High/Low risk = .70/.58

## Imbalanced Classification
![Screen Shot 2022-10-09 at 11 46 56 PM](https://user-images.githubusercontent.com/106411743/194796699-c4f70843-17a9-4878-bfc2-58ed5684bb35.png)

Balanced Accuracy: 0.7885466545953005

Precision: The precision is low for High-risk loans and is high for Low-risk loans.

Recall: High/Low risk = .70/.87



## Easy Ensemble AdaBoost Classifier
![Screen Shot 2022-10-09 at 11 47 48 PM](https://user-images.githubusercontent.com/106411743/194796755-871ef2aa-94ee-4288-9e75-37a9a2a7e39a.png)

Balanced Accuracy: 0.9316600714093861

Precision: The precision is low for High-risk loans and is high for Low-risk loans.

Recall: High/Low risk = .92/.94


## Summary: 

When using the balanced accuracy method the results range from 0 and 1. the closer the results are to one the better he model is.  For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models balanced accuracy was below .80 which is not as good. All the models had around the same results for the precision which was low for High-risk loans and is high for Low-risk loans. And for the recall score the Easy Ensemble AdaBoost Classifier had the highest score with .92 for highrisk and .94 for low risk.This makes Easy Ensemble AdaBoost Classifier as the best machine learning model to use for further credit card analysis.


