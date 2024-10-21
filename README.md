# SMS-SPAM-CLASSIFIER
This project is an implementation of an SMS Spam Classifier using machine learning techniques. The classifier is built using a Naive Bayes model and deployed as a web application using Streamlit. The goal of this project is to classify SMS messages as either "Spam" or "Not Spam".

# Project Overview
## Features ##
** Text Preprocessing : The SMS text messages undergo several preprocessing steps including lowercasing, tokenization, removal of special characters, stop words, and punctuation, and stemming.
** Feature Extraction : The preprocessed text is converted into numerical features using the TF-IDF vectorizer.
** Machine Learning Model : A Multinomial Naive Bayes classifier is trained on the processed data to predict whether a given SMS is spam or not.
** Web Application : The model is deployed as an interactive web application using Streamlit, allowing users to input SMS messages and get real-time predictions.
## Steps Involved ##
** Data Collection : The dataset contains SMS messages labeled as spam or ham (not spam).
** Exploratory Data Analysis (EDA) : Initial analysis to understand the structure and distribution of the data.
** Data Preprocessing :
Convert text to lowercase.
Tokenize the text.
Remove special characters, stop words, and punctuation.
Apply stemming to reduce words to their root forms.
Feature Extraction: Use TF-IDF vectorizer to convert text into numerical features.
Model Building: Train a Multinomial Naive Bayes classifier on the training data.
Model Evaluation: Evaluate the model's performance using accuracy, precision, and confusion matrix.
Web App Deployment: Deploy the model using Streamlit, providing a user-friendly interface for SMS classification.

## Interact with the App ##

Enter an SMS message in the input box.
Click on the "Predict" button to classify the message as Spam or Not Spam.
## Project Files ##
** app.py: The main Streamlit app script.
** vectorizer.pkl: Pickled TF-IDF vectorizer.
** model.pkl: Pickled Naive Bayes model.
