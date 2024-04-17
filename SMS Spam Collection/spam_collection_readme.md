
# SMS Spam Collection

Welcome to the **SMS Spam Collection** project! In this repository, we focus on predicting whether an SMS message is spam or legitimate (ham). We utilize natural language processing (NLP) techniques and machine learning algorithms to classify SMS messages.

## Purpose

The primary goal of this project is to develop a model that accurately distinguishes between legitimate (ham) messages and unwanted (spam) messages in a dataset of SMS messages.

## Dataset

The dataset used for this project is the **"SMS Spam Collection"** from the UCI Machine Learning Repository. It contains a collection of **5,574 SMS messages**, labeled as spam or ham. You can download the dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection).

The dataset file (**sms_spam_dataset.csv**) contains two columns:
- **label**: Indicates whether the message is spam (1) or ham (0).
- **text**: The actual text content of the SMS message.

## Contents

1. **Exploratory Data Analysis (EDA)**: We analyze the dataset to gain insights into spam and ham patterns.
2. **Data Preprocessing**: We clean and preprocess the text data for model training.
3. **Model Building**: We experiment with various machine learning algorithms (such as Naive Bayes, logistic regression, and support vector machines) to predict SMS spam.
4. **Model Evaluation**: We assess model performance using metrics like accuracy, precision, recall, and F1-score.
5. **Deployment**: We deploy the best-performing model using Streamlit for interactive use.

## Getting Started

1. Clone this repository to your local machine.
2. Place the **sms_spam_dataset.csv** file in the project directory.
3. Run the **sms_spam_detection.py** script to train and evaluate the spam detection model.
4. Modify the **predict** function in the script to predict the label (spam/ham) of new SMS messages.

## Model Performance

The trained model achieved an accuracy of **97.10%** and a precision of **100%** on the test set. It performed well in terms of recall and F1-score as well.

Feel free to contribute, modify, or use the code according to the terms of the license.
