# Naive Bayes Classifier for 3-Label Sentiment Classification

This repository contains the homework assignment for the AI course, which we implemented, focusing on a Naive Bayes classifier for sentiment classification with three labels: Positive, Negative, and Neutral. The assignment included training, evaluation, and testing subsets of the dataset.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Assignment Details](#assignment-details)
  - [Naive Bayes Classifier Structure](#naive-bayes-classifier-structure)
  - [Laplacian Smoothing](#laplacian-smoothing)
  - [3-Label Classification](#3-label-classification)
- [Evaluation](#evaluation)

## Introduction
This homework assignment aimed to help students understand and implement a Naive Bayes classifier for sentiment analysis. The task was to classify text data into three sentiment labels: Positive, Negative, and Neutral. We provided students with training and evaluation subsets of the dataset and expected them to implement a Naive Bayes classifier with Laplacian smoothing.

## Dataset
The dataset was divided into three subsets:
- **Train Set:** Used for training the model.
- **Eval Set:** Used for evaluating the model during development.
- **Test Set:** Used by TAs to evaluate the final submissions after the deadline.

## Assignment Details

### Naive Bayes Classifier Structure
The homework PDF we provided explained the structure of a Naive Bayes binary classifier. Students were required to extend this structure to handle three labels. The key components included:
- **Tokenization:** Breaking down text into individual words or tokens.
- **Probability Calculation:** Calculating the probability of each word given a class.
- **Classification:** Using the calculated probabilities to classify new text data.

### Laplacian Smoothing
Laplacian smoothing was used to handle the problem of zero probabilities in the Naive Bayes classifier. The formula for Laplacian smoothing is as follows:
\[ P(w|c) = \frac{count(w,c) + 1}{count(c) + |V|} \]
where:
- \( P(w|c) \) is the probability of word \( w \) given class \( c \)
- \( count(w,c) \) is the number of times word \( w \) appears in documents of class \( c \)
- \( count(c) \) is the total number of words in documents of class \( c \)
- \( |V| \) is the size of the vocabulary

### 3-Label Classification
Students needed to adapt the Naive Bayes classifier to handle three sentiment labels:
- **Positive**
- **Negative**
- **Neutral**

## Evaluation
After the submission deadline, we evaluated the models using a test set.
