# Sentiment Analysis on APERTI BUMN University Reviews

This project focuses on performing sentiment analysis on user reviews of APERTI BUMN universities. Using machine learning and natural language processing (NLP) techniques, it aims to classify the sentiment of each review as **positive**, **neutral**, or **negative**.

## Project Overview

The rise of online reviews regarding educational institutions calls for automated sentiment analysis tools to understand public opinion efficiently. This project leverages a supervised learning approach, using labeled review data obtained via the **OpenAI API** for automated sentiment annotation.

## Objectives

- Automatically label raw user reviews using OpenAI's language model.
- Perform thorough preprocessing and handle data imbalance using SMOTE.
- Compare three machine learning models: **SVM**, **Random Forest**, and **Logistic Regression**.
- Fine-tune hyperparameters and evaluate performance improvements.
- Determine the most effective model for sentiment classification.

## Dataset

- **Source**: Combined dataset from multiple APERTI BUMN university reviews.
- **Size**: 870 samples (after balancing).
- **Classes**: `positive`, `neutral`, `negative`
- **Format**: CSV

## Features & Preprocessing

- Lowercasing & text cleaning
- Punctuation and whitespace removal
- Non-standard word normalization
- Tokenization and stopword removal
- TF-IDF vectorization
- SMOTE oversampling to balance classes

## Exploratory Data Analysis (EDA)

- Class distribution before and after SMOTE
- Word frequency visualization
- Sentiment distribution bar charts

## Models Used

| Model               | Accuracy (Before Tuning) | Accuracy (After Tuning) |
|--------------------|--------------------------|-------------------------|
| SVM                | 91.37%                   | **97.58%**              |
| Logistic Regression| 89.42%                   | 92.30%                  |
| Random Forest      | 68.97%                   | 71.26%                  |

## Best Model

The **Support Vector Machine (SVM)** with RBF kernel and tuned hyperparameters (`C=10`, `gamma='scale'`) achieved the best performance with 97.58% accuracy.

## Tools & Libraries

- Python
- Scikit-learn
- imbalanced-learn (SMOTE)
- OpenAI API
- Pandas, NumPy
- Matplotlib, Seaborn


