# Credit_Risk_Analysis
Module 17 Challenge

# Overview:
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. For this project, a credit card credit dataset from LendingClub, a peer-to-peer lending services company, was used to oversample the data using the RandomOverSampler and SMOTE algorithms, and the data was undersampled using the ClusterCentroids algorithm. Then, a combinatorial approach of over- and undersampling using the SMOTEENN algorithm was used. Two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier were also compared, to predict credit risk. Performance of these models were evaulated with recomendations provided.  

# Results: 

- Oversampling
  - Balanced accuracy score 64%  
  - Precision 99%
  - Recall scores 60%

![Naive_Random_Oversampling](https://user-images.githubusercontent.com/95321969/163877029-7ebfb9d4-ce1b-4cc1-8ef0-05635a9b4733.png)

- SMOTE Oversampling
  - Balanced accuracy score 66%
  - Precision 99%
  - Recall scores 69%

![Smote](https://user-images.githubusercontent.com/95321969/163877394-cc47846d-d56e-4fb0-a244-80115d7eb50e.png)

- Undersampling
  - Balanced accuracy score 66%
  - Precision 99%
  - Recall scores 55%

![Undersampling](https://user-images.githubusercontent.com/95321969/163877560-b7abb2cc-1a61-44fc-8f01-271181278d66.png)

- Combination (Over and Under) Sampling
  - Balanced accuracy score 59%
  - Precision 99%
  - Recall scores 57%

![ComboSamp](https://user-images.githubusercontent.com/95321969/163877705-73fa1231-e930-46f5-bc56-715714873921.png)

- Balanced Random Forest Classifier
  - Balanced accuracy score 79%
  - Precision 99%
  - Recall scores 91%

![BalancedRandomForrestClassifier](https://user-images.githubusercontent.com/95321969/163877858-d8740720-c114-4151-b648-014e373087c5.png)

- Easy Ensemble AdaBoost Classifier
  - Balanced accuracy score 93%
  - Precision 99%
  - Recall scores 94%

![EasyEnsembleAdaBoostClassifier](https://user-images.githubusercontent.com/95321969/163877971-5aaa83dd-a1e7-4f7a-a5fd-e2ba131406ea.png)

## Summary

After analyis, the recomendation would be to use the Easy Ensemble AdaBoost Classifier, since the Balanced Accuracy score is 93%, Precision is 99%, and 
Recall score is 94%. The rest of the models have Balanced Accuracy scores ranging from 59% to 79% with Recall scores rangining from 55% to 91%. The ensemble models overall were better to predict credit risk, based on overall scores.

