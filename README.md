# Fake-News-Detection-Model

A machine learning project to detect fake news articles using supervised classification algorithms. This project leverages natural language processing (NLP) techniques to distinguish between real and fake news stories, offering a hands-on demonstration of data preprocessing, feature engineering, and model evaluation.

## Project Overview

This project classifies news articles as **"True"** or **"Fake"** based on their textual content. It includes:

- Data ingestion from CSV files
- Exploratory Data Analysis (EDA)
- Text vectorization using TF-IDF
- Model training using Logistic Regression
- Performance evaluation using accuracy, confusion matrix, and ROC-AUC
- Visualizations to support interpretability

## Dataset

Two datasets were used:

- `True_stories.csv` — Contains legitimate news articles
- `Fake_stories.csv` — Contains fabricated news articles

Each dataset includes text-based features such as:
- `title`
- `text`
- `subject`
- `date`

The datasets were merged and labeled for binary classification (`1 = Real`, `0 = Fake`).

## Model Used

- **Logistic Regression**

Text preprocessing pipeline includes:

- Lowercasing
- Stopword removal
- Tokenization
- TF-IDF vectorization

## Performance Metrics

Evaluation was based on:

- **Accuracy**
- **Precision / Recall / F1-score**
- **Confusion Matrix**
- **ROC Curve and AUC Score**

Logistic Regression achieved **over 90% accuracy** on the validation set.

## Key Learnings

- Text classification using TF-IDF and logistic regression
- Importance of preprocessing in NLP
- How ROC-AUC complements accuracy for imbalanced datasets
- Evaluating model robustness with confusion matrices

## Files in Repository

- `News_Classifier.ipynb` — Main notebook with code and analysis
- `True_stories.csv` — Real news articles
- `Fake_stories.csv` — Fabricated news articles

## Author

Aditya Arte  
MBA + Business Analytics Dual Degree Candidate  
Hult International Business School  
[LinkedIn Profile](https://www.linkedin.com/in/aditya-arte/)
