# Email Spam Detection

## Overview

This project uses **Machine Learning** to classify emails as **spam or not spam** based on their text content. It is part of my **Oasis Infobyte Data Science Internship** to implement practical NLP classification models.

## Dataset

- **Source:** Kaggle SMS Spam Collection Dataset
- Contains labelled SMS messages as 'spam' or 'ham' (not spam).

## Technologies Used

- Python
- Pandas, NumPy
- Scikit-learn
- Natural Language Processing (CountVectorizer, TfidfVectorizer)
- Naive Bayes Classifier
- Jupyter Notebook

## Task Workflow

1. Load and explore dataset
2. Preprocess text data
3. Vectorize using CountVectorizer/TfidfVectorizer
4. Train Naive Bayes classifier
5. Evaluate using accuracy and classification report
6. Save the model with joblib

## Installation

```bash
pip install pandas numpy scikit-learn joblib
