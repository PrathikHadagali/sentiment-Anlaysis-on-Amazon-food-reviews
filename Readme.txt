In this project you will go through a Natural Language Processing Python Project creating a Sentiment Analysis classifier with NLTK's VADER and Huggingface Roberta Transformers. The project is to classify the seniment of amazon customer reviews. 🤗  provides some great open source models for NLP: https://huggingface.co/models
. We will look at the difference between model outputs from the two packages and compare the results. Seniment analysis is an important tool for data scientists to use in laguage modeling.

Sentiment Analysis in Python¶

In this project we will be doing some sentiment analysis in python using two different techniques:

VADER (Valence Aware Dictionary and sEntiment Reasoner) - Bag of words approach
Roberta Pretrained Model from 🤗
Huggingface Pipeline.

Step 0. Read in Data and NLTK Basics

Step 1. VADER Seniment Scoring
We will use NLTK's SentimentIntensityAnalyzer to get the neg/neu/pos scores of the text.

This uses a "bag of words" approach:
Stop words are removed
each word is scored and combined to a total score.

Step 3. Roberta Pretrained Model
Use a model trained of a large corpus of data.
Transformer model accounts for the words but also the context related to other words.

Compare Scores between models

Step 3. Combine and compare

Step 4: Review Examples:
Positive 1-Star and Negative 5-Star Reviews
Lets look at some examples where the model scoring and review score differ the most.

Extra: The Transformers Pipeline
Quick & easy way to run sentiment predictions
