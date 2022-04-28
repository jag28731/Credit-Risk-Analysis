# Credit Risk Analysis

## Overview of Project
Jill commended me for all my hard work. Piece by piece, I built up my skills in data preparation, statistical reasoning, and machine learning. I am now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, I will need to employ different techniques to train and evaluate models with unbalanced classes. Jill asked me to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

### Purpose
In this project, I used the credit card credit dataset from LendingClub, a peer-to-peer lending services company. I oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. I used a combinatorial approach of oversampling and undersampling using the SMOTEENN algorithm. I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Credit Risk Results
Below are the results after my evaluation:

### Naive Random Oversampling
The balanced accuracy score is XX%, the precision score is XX% and the recall score is XX%.

![1]()

### SMOTE Oversampling
The balanced accuracy score is XX%, the precision score is XX% and the recall score is XX%.

![2]()

### Undersampling
The balanced accuracy score is XX%, the precision score is XX% and the recall score is XX%.

![3]()

### Combination (Over and Under) Sampling
The balanced accuracy score is XX%, the precision score is XX% and the recall score is XX%.

![4]()

### Balanced Random Forest Classifier
The balanced accuracy score is XX%, the precision score is XX% and the recall score is XX%.

![5]()

### Easy Ensemble AdaBoost Classifier
The balanced accuracy score is XX%, the precision score is XX% and the recall score is XX%.

![6]()

## Credit Risk Summary
Summary and a recommendation on which model to use, or there is no recommendation with a justification
