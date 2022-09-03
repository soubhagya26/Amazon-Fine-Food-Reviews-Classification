# Amazon-Fine-Food-Reviews-Classification
Sentiment Analysis
Aim : To determine the sentiment of a given review. (Negative/ Neutral/ Positive)
ML Task : Supervised Learning Multi-Class Text Classification
Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews

The dataset consists of reviews of fine foods from Amazon.

Number of reviews: 568,454
Number of users: 256,059
Number of products: 74,258
Timespan: Oct 1999 - Oct 2012
Number of Attributes/Columns in data: 10
Approach:
Classified sentiment based on review text, performed data cleaning and pre-processing by Stemming, stop-word removal, and Lemmatization. Class imbalanced problem handled by under sampling and for train-test splitting time-based sampling was used. Feature extracted using Bag of Words, TF-IDF, Average Word2Vec, TF-IDF Word2Vec. Applied Logistic Regression, Random Forest Classification, Support Vector Machine, Naïve Bayes, K-Nearest Neighbors with Hyperparameter tuning. Used Accuracy, Precision, Recall and F1-Score as metrics for comparison. Best Model was Logistic Regression with TF-IDF having accuracy 0.93.
![185122631-7136a846-5eb1-48b7-be79-a598716dc2f5](https://user-images.githubusercontent.com/98471328/188264336-dc07a22e-4210-4fee-b1b7-1e35fc574918.jpg)


Attribute Information:

Id

ProductId - unique identifier for the product

UserId - unqiue identifier for the user

ProfileName

HelpfulnessNumerator - number of users who found the review helpful

HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not

Score - rating between 1 and 5

Time - timestamp for the review

Summary - brief summary of the review

Text - text of the review
