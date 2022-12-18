# An analysis of Credit Risk

## Overview of Project
    This project is used to determine and predict credit risk using supervised machine learning models.
### Purpose
    The purpose of this project is to use different machine learning models to study alot of given information regarding credit risk and try to predict credit risk for data which doesn't contain the credit risk. The different models will study a list of models and try to predict the credit risk based off other given information.

## Results
    The following is a list of results and scores for all 6 different models, the results will be analyzed with the accompying pictures to determine how well they each performed and how relaible they are in predicting credit risk. 
### Supervised Machine Learning Models:

### Model 1 RandomOverSampler:
    The balanced accuracy score is about 0.66, with a very low precision of 0.01 for high risk, and 1 for low risk, the recall of 0.71 for high risk is pretty good with a worse 0.6 for low risk.
![](/images/model1.png)
### Model 2 SMOTE:
    The balanced accuracy score is about 0.66, with a very low precision of 0.01 for high risk, and 1 for low risk, the recall of 0.63 for high risk is less than the previous model with a higher score of 0.69 for low risk.
![](/images/model2.png)
### Model 3 ClusterCentroids:
    The balanced accuracy score is only 0.56, with a very low precision of 0.01 for high risk, and 1 for low risk, the recall of 0.61 for high risk and the 0.52 for low risk is the lowest scores so far.
![](/images/model3.png)
### Model 4 SMOTEENN:
    The balanced accuracy score is about 0.64, with a very low precision of 0.01 for high risk, and 1 for low risk, the recall of 0.72 for high risk is pretty good with a worse 0.57 for low risk. Overall its slightly worse than model 1.
![](/images/model4.png)
### Model 5 BalancedRandomForestClassifier:
    The balanced accuracy score is pretty good at 0.79, with a very low but improved precision of 0.03 for high risk, and 1 for low risk, the recall of 0.70 for high risk is pretty good with a much better 0.87 for low risk. Its the best model so far especially for predicitng low risk.
![](/images/model5.png)
### Model 6 EasyEnsembleClassifier:
    The balanced accuracy score is very good at 0.93, with a still low but improved precision of 0.09 for high risk, and 1 for low risk, the recall of 0.92 for high risk is pretty good with a much better 0.94 for low risk. Its the best model so of the 6 for every score.
![](/images/model6.png)

## Summary
    Of the 6 different models tested, the last one, the Easy Ensemble Classifier returns the highest scores for all of them.
### Recommendation:
    The model has a very high balanced accuracy score and very high scores for the recall for both high risk and low risk, meaning its very good at prediciting negative results, which in this case means prediciting low risk scores accurately. Given this information I would recommend using this model to predict who to lend money to since its able to predict which ones are low risk very accuratly, predicting only a few false negatives. The only drawback of the model is that its still bad at predicting too many false positives, which in this case means flagging people as high risk even when they are not. In this case the precision is not as important as the recall since that only means we are lending to a few less people than we would otherwise, not lending to people with high risk is more important to lower the overall risk of lending.
