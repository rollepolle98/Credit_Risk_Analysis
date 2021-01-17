# Credit_Risk_Analysis

## Overview and Purpose

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. In this project I am tasked with trying multiple different undersampling techniques in order to retrive a lgistic regression. After deploying multiple different techniques, SMOTEENN and Balanced Random Forest classifier will be use to model the algorithm. The purpose of this analysis is to experiment with creating a machine learning model that would most accurately predict credit risk by applying multiple different models and looking at the analysis in order to determine which is the best fit.


## Results
### Logistic Regression (LR) with Random Over Sampling
balanced accuracy score: .659,
precision: .01,
recall: .65



### LR with SMOTE
balanced accuracy score: .643,
precision: .01,
recall: .60



### LR with Cluster Centroid
balanced accuracy score: .611,
precision:.01,
recall:.66



### LoR with SMOTEENN
balanced accuracy score: .652,
precision: .01,
recall: .64



### Balanced Random Forest Classifier
balanced accuracy score: .681,
precision: .05,
recall: .41



### AdaBoost
balanced accuracy score: .883,
precision:.05,
recall:.86



## Summary
