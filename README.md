![Credit_risk_header](Resources/Supervised_ML_Credit_Risk.png)
# Credit_Risk_Analysis
## Overview
 We used supervised machine learning to evaluate credit risk.Credit risk is an inherently unbalanced problem, as good loans easily outnumber risky loans. Different techniques were used to train and evaluate models with unbalanced classes. Various libraries and algorithms were used to build and evaluate models using resampling.
 
 ## Purpose:
 1. Explain how a machine learning algorithm is used in data analytics.
 2. Create training and test groups from a given data set.
 3. Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
 4. Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
 5. Compare the advantages and disadvantages of each supervised learning algorithm.
 6. Determine which supervised learning algorithm is best used for a given data set or scenario.
 7. Use ensemble and resampling techniques to improve model performance.
 
 ## Results:
 The results for the six machine learning models including their respective balanced accuracy and recall scores are as follows:
 
 ## Random Oversampling
 ![Credit_risk](Resources/over_sampling_matrix.png)
 ![Credit_risk](Resources/over_sampling_report.png)
1. Balanced Accuracy: 0.8325468421491353
2. Recall: High/Low risk = .82/.87

## SMOTE Oversampling
![Credit_risk](Resources/Smote_matrix.png)
![Credit_risk](Resources/Smote_report.png)

1. Balanced Accuracy: 0.8440938486973113
2. Recall: High/Low risk = .82/.87

## Undersampling
![Credit_risk](Resources/undersample_matrix.png)
![Credit_risk](Resources/undersample_report.png)

1. Balanced Accuracy: 0.8440938486973113
2. Recall: High/Low risk = .82/.87

## Combination Under-Over Sampling
![Credit_risk](Resources/undersample_matrix.png)
![Credit_risk](Resources/undersample_report.png)

1. Balanced Accuracy: 0.8440938486973113
2. Recall: High/Low risk = .82/.87

## Balanced Random Forest Classifier
![Credit_risk](Resources/BFC_matrix.png)
![Credit_risk](Resources/BFC_report.png)

1. Balanced Accuracy: 0.759
2. Recall: High/Low risk = .63/.88

![Credit_risk](Resources/en_matrix.png)
![Credit_risk](Resources/en_report.png)

1. Balanced Accuracy: 0.759
2. Recall: High/Low risk = .63/.88

## Top 10 Important Features

![Credit_risk](Resources/top_10.png)

## Summary:

When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Combonation over and undersampling is the best model to choose with its .84 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Over and undersampling had the highest recall score, making it the final best machine learning model to choose for further credit card analysis.
