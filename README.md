Sentiment Analysis Using Machine Learning
## Objective

The objective of this project is to develop machine learning models to classify emotions from text samples using Natural Language Processing (NLP) techniques.

## The project performs:

Text preprocessing
Feature extraction using TF-IDF
Emotion classification using:
Naive Bayes
Support Vector Machine (SVM)
Model evaluation and comparison
Technologies Used
Python
Google Colab / Jupyter Notebook
Pandas
NumPy
NLTK
Scikit-learn
Matplotlib
Seaborn
Dataset

## The dataset contains:

Text comments/sentences
Emotion labels

Example emotions:

Joy
Anger
Fear

## Dataset columns:

Comment → Text data
Emotion → Target label
Project Workflow
1. Data Loading

The dataset is loaded using Pandas.

2. Text Preprocessing

The following preprocessing techniques are applied:

Lowercasing
URL removal
Number removal
Punctuation removal
Tokenization
Stopword removal
Benefits of Preprocessing
Removes noise from text
Improves model performance
Makes training faster
Focuses on meaningful words
Feature Extraction
TF-IDF Vectorization

## TF-IDF (Term Frequency - Inverse Document Frequency) converts text data into numerical vectors.

Advantages
Gives importance to meaningful words
Reduces importance of common words
Improves text classification accuracy

## Machine Learning Models
1. Naive Bayes

Naive Bayes is a probabilistic machine learning algorithm commonly used for text classification.

Advantages
Fast training
Simple implementation
Works well with text data
2. Support Vector Machine (SVM)

SVM is a supervised machine learning algorithm used for classification tasks.

Advantages
High accuracy
Handles high-dimensional data efficiently
Performs well for NLP tasks
Model Evaluation

## The models are evaluated using:

Accuracy Score
F1 Score
Classification Report
Confusion Matrix
Visualization

## The project includes:

Confusion Matrix visualization
Graphical comparison of models
Accuracy and F1-score comparison charts
Conclusion
Text preprocessing improved data quality.
TF-IDF successfully converted text into numerical features.
Both Naive Bayes and SVM models were trained successfully.
SVM achieved better performance for sentiment analysis tasks.
Naive Bayes provided faster training with simpler implementation.

Therefore, SVM is more suitable for emotion classification in this project.
