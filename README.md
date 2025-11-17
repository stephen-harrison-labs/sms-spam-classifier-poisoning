SMS Spam Classifier — TF–IDF + Naive Bayes (with Adversarial Robustness)

This notebook presents a fully reproducible, end-to-end machine-learning pipeline for SMS spam detection.
It covers every stage of the workflow, from raw text to evaluation, using a lightweight yet effective TF–IDF + Naive Bayes baseline.

The project includes:

Data cleaning & preprocessing

TF–IDF text vectorisation

Multinomial Naive Bayes classifier

Comprehensive evaluation: accuracy, precision, recall, F1-score, confusion matrix

Adversarial robustness test using random label-flip poisoning (0–20%)

The goal is to provide a clear, practical example of applied machine learning with an added security perspective—demonstrating not just how to build a text classifier, but how to examine its resilience when the training data is partially corrupted.
