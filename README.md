The study aims to delve into various algorithms, models, and methodologies used for sentiment analysis, also known as opinion mining. Sentiment analysis is a Natural Processing Language (NLP) that uses different techniques to translate the emotional tone or sentiment expressed in a piece of text, whether it’s positive, negative, or neutral (Bing Liu 2012).  Customer reviews, especially on platforms like Amazon or any e-commerce company, substantially influence purchase decisions, particularly for mobile electronic products because reviews help customers gauge the suitability of a product they are getting. These reviews serve as a compass for potential buyers, aiding them in gauging the suitability of a product for either personal use or as a gift. Analysing customer reviews allow brands to know what makes their customer happy or sad and use the review to improve their product and services. The aim of this research is to investigate different approaches used in sentiment analysis on Amazon reviews in order to gain insights into customer sentiment, measure product satisfaction levels, and understand the general sentiment distribution.
📌 What you're using:
You're leveraging a wide range of machine learning algorithms and tools for text preprocessing, vectorization, and model evaluation:

✅ Text Preprocessing & Feature Extraction:
TextBlob, NLTK – for sentiment polarity, text cleaning

TfidfVectorizer – for turning text into numerical features

SMOTE – to balance classes (important for imbalanced review sentiment data)

✅ Classifiers used:
Logistic Regression

Support Vector Machines (SVC)

Decision Tree & Random Forest

Extra Trees Classifier

Naive Bayes (BernoulliNB)

K-Nearest Neighbors (KNN)

✅ Evaluation Techniques:
Cross-validation

ROC-AUC score

Classification report

GridSearchCV for hyperparameter tuning
