# Sentimental-Analysis

# Introduction
Sentiment Analysis, also known as opinion mining, is the process of determining whether a piece of writing is positive, negative, or neutral. It is a technology that enables us to understand and analyze public sentiment towards various topics. This project aims to develop a sentiment analysis model to classify text based on sentiment.

# Dataset
The dataset used for this project was sourced from Kaggle. It consists of 50,000 IMDB movie reviews that were specifically selected for sentiment analysis. The sentiment of each review is binary, with a sentiment score of 0 for IMDB ratings less than 5 and a sentiment score of 1 for ratings greater than or equal to 7. The dataset includes a labeled training set of 25,000 reviews and a separate test set of another 25,000 reviews from different movies. Additionally, there are 50,000 IMDB reviews provided without rating labels.

# Classification Models
Several classification models were implemented and compared in this project to perform sentiment analysis. The models used include:

Logistic Regression
SGDClassifier (Stochastic Gradient Descent)
Naive Bayes Classifier (Gaussian, Multinomial, Bernoulli)
K-Nearest Neighbor Classifier
Random Forest Classifier
Decision Tree

# Evaluation
The performance of each classification model was evaluated using accuracy as the metric. Accuracy measures the ratio of correctly predicted observations to the total number of observations. The following accuracy scores were achieved:

Logistic Regression: 85.45%
SGDClassifier: 83.4%
Naive Bayes Classifier:
Gaussian: 80.4%
Multinomial: 83.95%
Bernoulli: 83.9%
K-Nearest Neighbor Classifier: 64.9%
Random Forest Classifier: 82.75%
Decision Tree: 68.8%

# Future Work
Future work on this project can explore additional techniques to improve the sentiment analysis model. Some suggestions for future enhancements include:

Trying other vectorizations to enhance the word matrix, such as removing subjects from sentences.
Exploring more complex models for analysis.
Investigating sentiment analysis on different datasets or domains.
Implementing techniques to handle sentiment analysis on social media data, such as sentiment analysis on Twitter or Facebook posts.
# Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to contribute by submitting a pull request.
