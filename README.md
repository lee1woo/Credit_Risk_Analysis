# Credit_Risk_Analysis

## Overview of the analysis

### Purpose

The purpose of this analysis was to employ different machine learning algorithm techniques to train and evaluate models with unbalanced classes to determine which sampling method and model should be used to predict credit risk. We are using the models to compare with LendingClub, a peer-to-peer lending services company. We used six models - RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier and EasyEnsembleClassifier.


## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Evaluation 

- Random Oversampling
![photo1](https://user-images.githubusercontent.com/102992388/198415255-ff4b063d-35ef-4767-a536-21c6a6e90ca7.png)

The balanced accuracy score was 65.72%.
As you can see, the precision score is low for high-risk class with just 1%. In comparison, it is high for the low-risk class (100%). 
The recall score  is similar to one another.

- SMOTE Oversampling

![photo2](https://user-images.githubusercontent.com/102992388/198415611-95ad155f-3975-4305-a671-80b7fab0c0bf.png)

The balanced accuracy score was 66.20%
The precision score for high-risk class was again low at 1%. The precision score for low-risk class again was 100%.

The recall score was again similar to one another. However, compared to the first oversampling, the low-risk class's recall score increased while it decreased for the high-risk class.

- Undersampling

![photo3](https://user-images.githubusercontent.com/102992388/198415930-9c9a1366-76ae-4c25-98e0-713b8a6bac8c.png)

Balanced accuracy score was 66.20%
The precision score reversed for low-risk and high-risk. 
The recall score decreased for low-risk class. 

### 

## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

### 
