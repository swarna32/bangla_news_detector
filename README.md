# Bangla News Detector

## Overview
This project aims to classify Bangla news articles into two classes: real and fake. The dataset is preprocessed to remove Bangla punctuation and stopwords, and a Bangla stemmer is used to reduce words to their root forms. SMOTE (Synthetic Minority Over-sampling Technique) is used for balancing the dataset. TF-IDF (Term Frequency-Inverse Document Frequency) is used for feature extraction. Several machine learning models are trained and their performances are evaluated.

## Dataset
- **Classes**: 2 (real and fake)
- **Data Preprocessing**:
  - **Bangla Punctuation Removal**: Removes punctuation marks from Bangla text.
  - **Bangla Stopwords Removal**: Removes common Bangla stopwords to reduce noise.
  - **Bangla Stemmer**: Reduces words to their root forms for normalization.
  - **SMOTE**: Balances the dataset by oversampling the minority class.

## Feature Extraction
- **TF-IDF**: Converts the text data into numerical features, where each term's weight reflects its importance within a document relative to the entire corpus.

## Model Training and Evaluation
The following machine learning models were trained and evaluated:
- **Naive Bayes (NB)**
- **Logistic Regression (LR)**
- **Decision Tree (DT)**
- **Gradient Boosting**
- **Support Vector Classifier (SVC)**
- **Voting Classifier**: Combines multiple models using hard and soft voting strategies.

## Model Evaluation
The performance of each model is evaluated using the following metrics:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**
