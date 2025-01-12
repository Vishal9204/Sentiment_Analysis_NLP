# Sentiment Analysis Using NLP

This project implements a sentiment analysis model to classify text data as positive or negative using various machine learning techniques.

## Features

- **Text Preprocessing**: 
  - Cleaning text by removing URLs and special characters.
  - Tokenizing and lemmatizing words.
  - Removing stopwords for noise reduction.

- **Machine Learning Models**:
  - Random Forest Classifier
  - Support Vector Machines (SVM)
  - Multinomial Naive Bayes

- **Evaluation Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1-score

## Project Workflow

1. **Data Preprocessing**:
   - Clean and normalize text data.
   - Tokenize and lemmatize words.
   - Remove stopwords to focus on meaningful words.

2. **Model Training**:
   - Train Random Forest, SVM, and Naive Bayes classifiers on preprocessed data.
   - Optimize models for robust and accurate classification.

3. **Model Evaluation**:
   - Assess the performance of each model using accuracy, precision, recall, and F1-score.

## Prerequisites

- Python 3.8 or higher
- Required Libraries:
  - `scikit-learn`
  - `nltk`
  - `pandas`
  - `numpy`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/sentiment-analysis-nlp.git
   cd sentiment-analysis-nlp
