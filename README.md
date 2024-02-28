# Named-Entity-Recognition
# UNDERSTANDING TEXT FROM DIFFERENT TYPES OF CONSUMER REVIEWS

Text Mining for AI Final Project Report
Authors: B.Yalcin, E.Erel, A.Ilbay, D.Gülal

## Introduction
In this project, NLP techniques such as Named Entity Recognition (NERC), Sentiment Analysis and Topic Analysis are applied to a set of restaurant, book, movie reviews with the goal of gaining a deeper understanding of customer opinions and preferences. In this way, we aim to detect sentiments and topics of the product reviews.

## Methodology 

Data for Sentiment analysis and Topic analysis is collected from book reviews, movie reviews, and restaurant reviews datasets, merged into one. The dataset consists of 4 columns: sentence id, text, sentiment, and topic. For NERC analysis Annotated Corpus dataset is used.

Feature extraction with:

NERC analysis: dataset trained with SVM. The motivation for using SVM with Annotated Corpus Dataset is because Support Vector Machines are commonly used in NLP tasks for classification and regression.

Sentiment analysis

VADER: rule-based sentiment analysis system using a lexicon of word- sentiment score pairs. The main motivation for selecting this approach is to make a clear distinction between the performances of rule-based and machine-learning systems during sentiment analysis.

Naive Bayes: Statistical classification method based on Bayes theorem. The motivation was to use a machine-learning algorithm with simplicity, speed and effectiveness.

Topic analysis

We used LDA to test how well it could predict our labels and used regression algorithms because they are simple, efficient and easy to use.
Gensim, LDA, Tf-idf, SVM
