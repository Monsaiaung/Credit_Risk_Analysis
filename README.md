# Credit_Risk_Analysis

## Overview of the analysis: Explain the purpose of this analysis.

The purpose of this project is to analyze credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. The project consists of employing different techniques to train and evaluate models with unbalanced classes. 

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Naive Random Oversampling

![Naive Random Oversampling](https://github.com/Monsaiaung/Credit_Risk_Analysis/blob/42d4bdb94c51a16727668b3080b83287c9a39a21/images/Naive%20Random%20Oversampling.png)

### SMOTE Oversampling

![SMOTE](https://github.com/Monsaiaung/Credit_Risk_Analysis/blob/42d4bdb94c51a16727668b3080b83287c9a39a21/images/SMOTE%20Oversampling.png)

### Undersampling

![Undersampling](https://github.com/Monsaiaung/Credit_Risk_Analysis/blob/42d4bdb94c51a16727668b3080b83287c9a39a21/images/Undersampling.png)

### Combination (Over and Under) Sampling

![Combo](https://github.com/Monsaiaung/Credit_Risk_Analysis/blob/42d4bdb94c51a16727668b3080b83287c9a39a21/images/Combination%20(Over%20and%20Under)%20Sampling.png)

### Easy Ensemble AdaBoost Classifier

![EEAC](https://github.com/Monsaiaung/Credit_Risk_Analysis/blob/42d4bdb94c51a16727668b3080b83287c9a39a21/images/Easy%20Ensemble%20AdaBoost%20Classifier.png)

### Balance Random Forest Classifier

![BRFC](https://github.com/Monsaiaung/Credit_Risk_Analysis/blob/42d4bdb94c51a16727668b3080b83287c9a39a21/images/Balanced%20Random%20Forest%20Classifier.png)

## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
