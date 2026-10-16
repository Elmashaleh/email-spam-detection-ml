# Email Spam Detection — Machine Learning

A Python machine learning project that classifies emails as **Spam or Ham** using Natural Language Processing (NLP) and supervised learning.

## Project Overview

This project processes raw email text, converts it into numerical features using **CountVectorizer (Bag-of-Words)**, and compares three classification algorithms.

**Technologies:** Python · Scikit-learn · Pandas · Matplotlib · Jupyter Notebook

## Models & Results

| Model | Precision | Recall |
|---|---:|---:|
| Naive Bayes | 98.72% | 81.05% |
| SGD Classifier | **98.95%** | 98.95% |
| Logistic Regression | 96.94% | **100%** |

Logistic Regression achieved **98.45% F1-score** on the test set, identifying all 95 spam emails while incorrectly flagging 3 legitimate emails.

## Workflow

1. Load and label spam/ham emails.
2. Split data into training and testing sets (80/20).
3. Extract text features using CountVectorizer.
4. Train and evaluate three classifiers.
5. Compare performance using precision, recall, F1-score, and confusion matrices.


## Author

**Motaz Mashaleh**  
Computer Engineering Undergraduate — Hashemite University

[GitHub Profile](https://github.com/Elmashaleh)
