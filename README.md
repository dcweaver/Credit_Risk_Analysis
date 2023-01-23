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

* EasyEnsembleClassifier:
![easyemsemble](/Resources/easy_ensemble.png)

* 