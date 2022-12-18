# An analysis of Credit Risk

## Overview of Project
    This project is used to determine and predict credit risk using supervised machine learning models.
### Purpose
    The purpose of this project is to use different machine learning models to study alot of given information regarding credit risk and try to predict credit risk for data which doesn't contain the credit risk. The different models will study a list of models and try to predict the credit risk based off other given information.

## Results
    The following is a list of results and scores for all 6 different models, the results will be analyzed with the accompying pictures to determine how well they each performed and how relaible they are in predicting credit risk. 
### Supervised Machine Learning Models:

### Model 1 RandomOverSampler:
    The trip duration for the bikes is generally fairly short, with the vast majority in under an hour, and most of those lasting less than 20 minutes.
![](/images/model1.png)
### Model 2 SMOTE:
    The majority of users are male, with a few being 'unknown' gender, however whatever their gender, the trip duration isn't affected much.
![](/images/model2.png)
### Model 3 ClusterCentroids:
    The number of trips are highest on weekdays from 5-7pm, followed by 7-9am, this is likely for people leaving and going to work. This assumption is backed up by the fact that the spread is much more even during the weekend.
![](/images/model3.png)
### Model 4 SMOTEENN:
    The gender doesn't seem to have any affect on the concentration of trips for any given time, male and female both seem to same distribution when they're more likely to get the bike.
![](/images/model4.png)
### Model 5 BalancedRandomForestClassifier:
    The trips are highest for subscribers on Thursday and Friday for male and female, while the non subscriber customers seems to be highest during the weekend.
![](/images/model5.png)
### Model 6 EasyEnsembleClassifier:
    The top starting locations are clustered in a certain area in Manhattan, with much fewer trips outside the island.
![](/images/model6.png)

## Summary
    The story gives some insights on the peak hours for trips and the locations of them broken down by geneder and customer type for the time the trips take place.
### Visualization 1:
    Getting starting and ending locations based on the genders or customer types would be helpful to see if there is any bias in locations for the gender and customer types and could help us understand the customers more.
### Visualization 2:
    Getting a breakdown of the trip times based on the age of customers could be helpful to see if there is a difference in trip times based on age and if so, to see if there's anyway to could encourage certain age groups to take longer or shorter trips depending on the data findings.
