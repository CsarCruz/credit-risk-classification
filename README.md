# Credit-risk-classification


##Purpose

This analysis was built to generate a logistic model that analyzes information to evaluate if an applicant has the variables to be a "healthy loan" or, on the opposite side, to be a "high-risk loan".


##Results

ORIGINAL DATA MODEL

* Accuracy: 99%
* Healthy loans precision: 100%
* High risk loans precision: 85%
* Healthy loans recall: 99%
* High risk loans recall: 91%


RESAMPLED DATA MODE

* Accuracy: 99%
* Healthy loans precision: 100%
* High risk loans precision: 84%
* Healthy loans recall: 99%
* High risk loans recall: 99%


##Summary
After analyzing the original data and resampled data results, we can see that they have a very similar behavior in accuracy and precision. The significant variation is in the high-risk loans recall, which is higher in the resampled data. In the resampled data, we can observe that the model is effective at capturing positive instances but has trouble avoiding false negatives. Meanwhile, in the original data analysis, we can observe that both instances are far away from giving accurate predictions.
