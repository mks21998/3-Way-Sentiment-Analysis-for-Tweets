# 3-Way-Sentiment-Analysis-for-Tweets

Overview
In this project, we'll build a 3-way polarity (positive, negative, neutral) classification system for tweets, without using NLTK's in-built sentiment analysis engine.

We'll use a logistic regression classifier, bag-of-words features, and polarity lexicons (both in-built and external). We'll also create our own pre-processing module to handle raw tweets.

Data Used
training.json: This file contains ~15k raw tweets, along with their polarity labels (1 = positive, 0 = neutral, -1 = negative). We'll use this file to train our classifiers.

develop.json: In the same format as training.json, the file contains a smaller set of tweets. We'll use it to test the predictions of our classifiers which were trained on the training set.
