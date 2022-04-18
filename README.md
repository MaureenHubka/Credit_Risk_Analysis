# Credit_Risk_Analysis
Module 17 Challenge

# Overview:
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

# Results: 

- Oversampling
- balanced accuracy score and the precision and recall scores o

![Naive_Random_Oversampling](https://user-images.githubusercontent.com/95321969/163877029-7ebfb9d4-ce1b-4cc1-8ef0-05635a9b4733.png)

- SMOTE Oversampling

![Smote](https://user-images.githubusercontent.com/95321969/163877394-cc47846d-d56e-4fb0-a244-80115d7eb50e.png)

- Undersampling

![Undersampling](https://user-images.githubusercontent.com/95321969/163877560-b7abb2cc-1a61-44fc-8f01-271181278d66.png)

- Combination (Over and Under) Sampling

![ComboSamp](https://user-images.githubusercontent.com/95321969/163877705-73fa1231-e930-46f5-bc56-715714873921.png)

- Balanced Random Forest Classifier

![BalancedRandomForrestClassifier](https://user-images.githubusercontent.com/95321969/163877858-d8740720-c114-4151-b648-014e373087c5.png)

- Easy Ensemble AdaBoost Classifier

![EasyEnsembleAdaBoostClassifier](https://user-images.githubusercontent.com/95321969/163877971-5aaa83dd-a1e7-4f7a-a5fd-e2ba131406ea.png)

## Summary
 
