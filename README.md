# Sports vs Politics Text Classification

## Problem Statement
Design a classifier that reads a text document and classifies it as Sport or Politics using machine learning techniques.

## Dataset
AG News Dataset
- World → Politics
- Sports → Sport
Binary classification task

## Feature Engineering
- Bag of Words (CountVectorizer)
- TF-IDF (Unigram)
- TF-IDF with Bigrams (n-grams)

## Machine Learning Models
- Multinomial Naive Bayes
- Linear Support Vector Machine
- Random Forest

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

## Best Model
Linear SVM achieved highest performance (~97.9% accuracy).

## Visualizations Included
- Class distribution
- Text length distribution
- Feature space size
- Top TF-IDF words
- PCA projection
- Model comparison plots

## How to Run
1. Open notebook in Google Colab or Jupyter.
2. Install required libraries.
3. Run all cells sequentially.

## Author
Sagnik Chandra