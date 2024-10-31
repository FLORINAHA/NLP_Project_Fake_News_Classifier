### Fake News Classifier ###

## Description
This project uses Natural Language Processing (NLP) and machine learning to classify news articles as true or fake. By analyzing patterns in textual content, this classifier helps users identify misleading or false news, providing a reliable tool for information verification.

## Features
Fake News Detection: Classifies articles as either true (authentic) or fake (misleading) using NLP techniques for text processing and analysis.

### Machine Learning Algorithms: 
The model compares multiple algorithms to evaluate their effectiveness for this task:
Naive Bayes: Useful for text classification tasks with a strong assumption of feature independence.
Random Forest: An ensemble method that reduces overfitting and improves accuracy by averaging predictions from multiple decision trees.
K-Nearest Neighbors (KNN): A non-parametric method that assigns class labels based on the majority class among the nearest neighbors.

### Tech Stack
Language: Python 3.1

### Libraries:
pandas and numpy for data manipulation
scikit-learn for machine learning and performance evaluation
nltk for NLP tasks, including tokenization, stop words removal, and lemmatization
TfidfVectorizer and CountVectorizer for feature extraction

