# Credit_Risk_Analysis

## Overview

Due to the nature of credit risk, there is an inherent uncertainty in assessing the risk as the number of good loans far outnumber the amount of risky loans. In order to combat this, multiple models and techniques were used to train and evaluate the unbalanced classes. 

The data was oversampled using the RamdomOverSampler and SMOTE algorithms. The data was then undersampled using the Cluster Centroids algorithm. Following this, a combination over and under sampling algorithm from SMOTEENN was used on the data. Finally using two models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier were used to predict the credit risk. 

#### Packages and models used:

* imbalanced-learn
* scikit-learn
* RandomOverSampler
* SMOTE algorithms
* SMOTEEN algorithm
* BalancedRandomForestClassifier (bias reduction model)
* EasyEnsemble (bias reduction model)

## Results

* Naive Random Oversampling:
![naive random oversampling](/Resources/naive_oversample.png)

* SMOTE Oversampling:
![smote oversample](/Resources/smote_oversampling.png)

* ClusterCentroid Undersampling:
![cluster undersampleing](/Resources/undersampling.png)

* Combination Over/Under:
![combination](/Resources/combination_sampling.png)

* Balanced Random Forest Classifier:
![balancedramdonforest](/Resources/balanced_random_forest.png)


* EasyEnsembleClassifier:
![easyemsemble](/Resources/easy_ensemble.png)


#### Accuracy Scores
Naive Oversampling - ~66%
SMOTE Oversampling - ~66%
ClusterCentrioid Undersampling - ~54%
Combination Over/Under Sampling - ~65%
Balanced Random Forest classifier - ~79%
EasyEmsemble Classifier - ~92%

Based on the accuracy scores for all of the models, the EasyEnsemble Clasifier model easily performs the best out of these six models with a score of 92% and would be the recommendation for this type of analysis going forward.

