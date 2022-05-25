# Overview of the Analysis

This analysis focuses on predicting credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, this challenge employs different techniques to train and evaluate models with unbalanced classes, using the imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

The first part of the analysis oversamples the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. A combinatorial approach of over-andundersampling using the SMOTEENN algorithm is also performed. Lastly, the challenge compares two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict risk.

# Results

Below images show the balanced accuracy score, confusion matrix, and imbalanced classification report for each machine learning model.

## Resampling Models to Predict Credit Risk

### Naive Random Oversampling

<img src="Images/NaiveRandomSamplig_AccScore.png">
<img src="Images/NaiveRandomSampling_cm.png">
<img src="Images/NaiveRandomSampling_cr.png">

### SMOTE Oversampling

<img src="Images/SMOTE_acc.png">
<img src="Images/SMOTE_cm.png">
<img src="Images/SMOTE_cr.png">

### Undersampling

<img src="Images/undersampling_Acc.png">
<img src="Images/undersampling_cm.png">
<img src="Images/undersampling_cr.png">

### Combination (Over and Under) Sampling

<img src="Images/Comb_Acc.png">
<img src="Images/Comb_cm.png">
<img src="Images/Comb_cr.png">

## Ensemble Classifiers to Predict Credit Risk

### Balanced Random forest classifier

<img src="Images/brfc_Acc.png">
<img src="Images/brfc_cm.png">
<img src="Images/brfc_cr.png">

### Easy Ensemble AdaBoost Classifier

<img src="Images/eec_Acc.png">
<img src="Images/eec_cm.png">
<img src="Images/eec_cr.png">

# Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
