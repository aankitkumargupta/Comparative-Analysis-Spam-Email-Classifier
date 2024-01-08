# Comparative Analysis of Spam Email Classifier 

This repository contains a Spam Email Classifier implemented using NLP techniques. The classifier is designed to distinguish between spam and non-spam (ham) emails. The dataset used for training and evaluation has a shape of (5171, 4).

# Data Preprocessing
The dataset undergoes several preprocessing steps:
Text Length Calculation: A new column 'length' is created to store the number of words in each row of the text column.

Tokenization: Tokenization is performed using the Natural Language Toolkit (nltk) for word tokenization. Commas and full stops are removed during this process.
Lemmatization: To maintain linguistic accuracy, lemmatization is chosen over stemming. This step involves reducing words to their base or root form.

# Exploratory Data Analysis (EDA) 
Exploratory Data Analysis (EDA) is conducted to better understand the dataset. This includes generating a pair plot, heatmap of correlation, and histograms of word length by label. The goal is to gain insights into the characteristics of spam and ham emails.

# Vectorization
The text data is transformed into numerical vectors using the Term Frequency-Inverse Document Frequency (TF-IDF) technique. This step is crucial for feeding the data into machine learning algorithms.

# Machine Learning Algorithms
Various machine learning algorithms are applied to the vectorized data. The following algorithms are used:
Naive Bayes
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Random Forest
Logistic Regression

The accuracy of each algorithm is measured and visualized using a bar plot. The results provide insights into the performance of each algorithm in classifying spam and ham emails.
