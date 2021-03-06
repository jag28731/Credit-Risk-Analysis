# Credit Risk Analysis

## Overview of Project
Jill commended me for all my hard work. Piece by piece, I built up my skills in data preparation, statistical reasoning, and machine learning. I am now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, I will need to employ different techniques to train and evaluate models with unbalanced classes. Jill asked me to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

### Purpose
In this project, I used the credit card credit dataset from LendingClub, a peer-to-peer lending services company. I oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersampled the data using the ClusterCentroids algorithm. I used a combinatorial approach of oversampling and undersampling using the SMOTEENN algorithm. I compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Credit Risk Results
Below are the results after my evaluation:

### Naive Random Oversampling
The balanced accuracy score is 66.14%, the precision score is 99% and the recall score is 60%.

![1](https://github.com/jag28731/Credit-Risk-Analysis/blob/main/Resources/Naive%20Random%20Oversampling.PNG)

### SMOTE Oversampling
The balanced accuracy score is 65.81%, the precision score is 99% and the recall score is 69%.

![2](https://github.com/jag28731/Credit-Risk-Analysis/blob/main/Resources/SMOTE%20Oversampling.PNG)

### Undersampling
The balanced accuracy score is 54.43%, the precision score is 99% and the recall score is 40%.

![3](https://github.com/jag28731/Credit-Risk-Analysis/blob/main/Resources/Undersampling.PNG)

### Combination (Over and Under) Sampling
The balanced accuracy score is 64.49%, the precision score is 99% and the recall score is 57%.

![4](https://github.com/jag28731/Credit-Risk-Analysis/blob/main/Resources/Combination%20Sampling.PNG)

### Balanced Random Forest Classifier
The balanced accuracy score is 77.43%, the precision score is 99% and the recall score is 88%.

![5](https://github.com/jag28731/Credit-Risk-Analysis/blob/main/Resources/Balanced%20Random%20Forest%20Classifier.PNG)

### Easy Ensemble AdaBoost Classifier
The balanced accuracy score is 91.79%, the precision score is 99% and the recall score is 94%.

![6](https://github.com/jag28731/Credit-Risk-Analysis/blob/main/Resources/Easy%20Ensemble%20AdaBoost%20Classifier.PNG)

## Credit Risk Summary
I used the above models to determine which loans are the highest risk. In the first four models, I used Naive Random Oversampling, SMOTE Oversampling, Undersampling, and a combination of both. The last two models I used Balanced Random Forest and Easy Ensemble AdaBoost classifiers. In the first four models, the accuracy score was not as high as the last two models and in the last two models, the recall score was higher than the first four models. The precision score was the same for all the models. I would recommend the Easy Ensemble AdaBoost Classifier because you want to have an overall good balance of scores between the accuracy, precision, and recall scores. The Easy Ensemble Adaboost Classifier has the highest accuracy score with 91.79% and recall score with 94% with the precision score being the same as the rest, 99%. 
