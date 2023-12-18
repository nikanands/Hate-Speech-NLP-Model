# Natural Language Processing (NLP) Model

## Introduction
Natural Language Processing (NLP) is a form of artificial intelligence (AI) that enables computers to understand human language, whether spoken or written. In this notebook, we are going to build a model and find out how our model is working based on the data. The data is taken from Kaggle. The data link is the following.
Data: [Hate Speech Dataset](https://www.kaggle.com/datasets/thedevastator/hate-speech-and-offensive-language-detection/data)

## About Data
The data is about _hate speech and offensive language_. The data is tweets of many persons. The dataset has 6 columns and 24783 rows.

## About Model
We are going to build a Deep Learning Model using LSTM and Dense as our main layer. But to make our model perform better we have to preprocess the data beforehand. we are using multiple functions to remove unnecessary texts, tags, or symbols from the tweets so that the model should take only that data which have some weight in finding the target.

### Let's check the model.
