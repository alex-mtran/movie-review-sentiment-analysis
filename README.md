# Movie Review Sentiment Analysis

This project performs sentiment analysis on critic reviews scraped from Rotten Tomatoes, with the goal of predicting whether a critic gave a movie a "fresh" (positive) or "rotten" (negative) rating based solely on the text of their review. We explored a range of supervised and unsupervised techniques including KNN, Naive Bayes, Decision Trees, Random Forest, KMeans Clustering, TextBlob, and VADER to evaluate how well different approaches handle the challenges of natural language classification.

Our best performing model was Random Forest at ~86% accuracy, while the primary challenge across models was the curse of dimensionality stemming from the large number of unique words across the dataset. The full project report details our methodology, data analysis, and findings.
