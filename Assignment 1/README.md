# Assignment 1 — Language Modeling and Text Classification

## Overview

This project explores two fundamental Natural Language Processing tasks:

1. Building statistical N-Gram language models for next-word prediction and text generation.
2. Performing news article classification using traditional machine learning algorithms.

## Part 1: N-Gram Language Modeling

### Dataset
- WikiText-2

### Implemented Features
- Text preprocessing and normalization
- Unigram, Bigram, and Trigram models
- Laplace smoothing
- Perplexity evaluation
- Model saving and loading
- Text generation from a user prompt

### Evaluation
Different N-gram configurations were compared using perplexity on the test set.

---

## Part 2: News Classification

### Dataset
- AG News

### Implemented Models

#### Naive Bayes
- From-scratch NumPy implementation
- Scikit-Learn implementation

#### Logistic Regression
- From-scratch NumPy implementation
- Scikit-Learn implementation

### Evaluation Metrics
- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-Score

## Technologies
- Python
- NumPy
- Scikit-Learn
- Hugging Face Datasets
- Jupyter Notebook