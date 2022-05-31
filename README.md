# Credit_Risk_Analysis

## Overview of the analysis: Explain the purpose of this analysis.

The purpose of this project is to analyze credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. The project consists of employing different techniques to train and evaluate models with unbalanced classes. 

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Naive Random Oversampling

![Naive Random Oversampling](https://github.com/Monsaiaung/Credit_Risk_Analysis/blob/42d4bdb94c51a16727668b3080b83287c9a39a21/images/Naive%20Random%20Oversampling.png)

The balanced accuracy score for this model is around 65%. With the high number of the low_risk population, its precision is almost 100% while the sensitivity of 68%.

### SMOTE Oversampling

![SMOTE](https://github.com/Monsaiaung/Credit_Risk_Analysis/blob/42d4bdb94c51a16727668b3080b83287c9a39a21/images/SMOTE%20Oversampling.png)

The balanced accuracy score for this model is around 63%. With the high number of the low_risk population, its precision is almost 100% while the sensitivity of 64%.

### Undersampling

![Undersampling](https://github.com/Monsaiaung/Credit_Risk_Analysis/blob/42d4bdb94c51a16727668b3080b83287c9a39a21/images/Undersampling.png)

The balanced accuracy score for this model is around 51%. With the high number of the low_risk population, its precision is almost 100% while the sensitivity of 44%.

### Combination (Over and Under) Sampling

![Combo](https://github.com/Monsaiaung/Credit_Risk_Analysis/blob/42d4bdb94c51a16727668b3080b83287c9a39a21/images/Combination%20(Over%20and%20Under)%20Sampling.png)

The balanced accuracy score for this model is around 62%. With the high number of the low_risk population, its precision is almost 100% while the sensitivity of 54%.

### Easy Ensemble AdaBoost Classifier

![EEAC](https://github.com/Monsaiaung/Credit_Risk_Analysis/blob/42d4bdb94c51a16727668b3080b83287c9a39a21/images/Easy%20Ensemble%20AdaBoost%20Classifier.png)

The balanced accuracy score for this model is around 93%. With the high number of the low_risk population, its precision is almost 100% while the sensitivity of 94%.

### Balance Random Forest Classifier

![BRFC](https://github.com/Monsaiaung/Credit_Risk_Analysis/blob/42d4bdb94c51a16727668b3080b83287c9a39a21/images/Balanced%20Random%20Forest%20Classifier.png)

The balanced accuracy score for this model is around 78%. With the high number of the low_risk population, its precision is almost 100% while the sensitivity of 91%.

## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
