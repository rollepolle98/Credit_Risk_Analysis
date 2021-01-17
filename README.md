# Credit_Risk_Analysis

## Overview and Purpose

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. In this project I am tasked with trying multiple different undersampling techniques in order to retrive a lgistic regression. After deploying multiple different techniques, SMOTEENN and Balanced Random Forest classifier will be use to model the algorithm. The purpose of this analysis is to experiment with creating a machine learning model that would most accurately predict credit risk by applying multiple different models and looking at the analysis in order to determine which is the best fit.


## Results
### Logistic Regression (LR) Naive Random Oversampling

![](Analysis/Balanced_Accuracy/Naive_Random.png)

* precision: 0.01
* recall: 0.74
* f1: 0.02

### LR with SMOTE


![](Analysis/Balanced_Accuracy/SMOTE.png)

* precision: 0.01
* recall: 0.63
* f1: 0.02

### LR with Undersampling (Cluster Centroid)

![](Analysis/Balanced_Accuracy/Undersampling.png)

* precision: 0.01
* recall: 0.67
* f1: 0.01



### LoR with SMOTEENN


![](Analysis/Balanced_Accuracy/Undersampling.png)

* precision: 0.01
* recall: 0.70
* f1: 0.02

### Balanced Random Forest Classifier

![](Analysis/Balanced_Accuracy/Balanced_Random_Forest.png)

* precision: 0.01
* recall: 0.70
* f1: 0.06

### AdaBoost

![](Analysis/Balanced_Accuracy/Easy_Ensemble.png)

* precision: 0.09
* recall: 0.92
* f1: 0.16

## Summary

Based on all of the analysis and testing it seems as if the AdaBoost performed the best across all three metrics. They key metric that it performed best on was recall, recall is far more important than precision for this task. AdaBoost preformed the best in the average of all metrics and caught 93% of the fraud cases however it still lacks precision which is a distinguishing factor in uncovering all of these cases. While there may be some flaws in AdaBoost, it seems like it is the best model for our data in order to catch the most fraud claims.
