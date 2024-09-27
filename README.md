**Project Overview**
This project addresses the problem of determining whether two questions on Quora are semantically similar. The task involves building a classification model that takes in pairs of questions and predicts whether they are duplicates. This problem is approached using Natural Language Processing (NLP) techniques to extract meaningful features from the text data.

**Steps Performed**
1. Exploratory Data Analysis (EDA)
Performed initial exploration to understand the dataset.
Analyzed the distribution of question pairs, duplicates vs non-duplicates, and identified patterns or imbalances in the data.
2. NLP Feature Extraction
Utilized advanced NLP techniques to convert text data into numerical representations for machine learning models.
Employed Word2Vec (W2V) and GloVe embeddings to capture semantic meaning and context from the questions.
Preprocessed the text data by removing stop words, lowercasing, and tokenizing the questions to prepare them for embedding.
3. Data Preprocessing
Cleaned the text data by handling missing values, punctuation, and special characters.
Standardized text data and ensured consistent formatting across both questions in each pair.
4. Model Implementation
Decision Tree: Implemented as a baseline model to classify question pairs.
Logistic Regression: Used to perform binary classification with the embedded text features.
Support Vector Machine (SVM): Applied for more complex decision boundaries to separate duplicate and non-duplicate question pairs.
5. Cross-Validation and Model Tuning
Applied cross-validation techniques to tune hyperparameters and validate model performance.
Tested models on validation sets to avoid overfitting and improve generalization.
6. Model Evaluation
Evaluated models using metrics such as accuracy, precision, recall, and F1-score to assess classification performance.
Compared models to find the best-performing approach for the task.
7. Pipeline for New Data
Developed a full pipeline that includes preprocessing, feature extraction (W2V/GloVe), and model prediction for unseen question pairs.

**Results**
Models were tested and evaluated based on classification metrics.
Logistic Regression and SVM showed promising results, particularly when using GloVe embeddings.
**Requirements**
The project includes a requirements file (requirements.txt) with all necessary libraries for running the pipeline, including NLP packages like gensim and sklearn for model building.
**Problem Objective**
The goal of the project was to classify pairs of questions as either duplicates or non-duplicates using NLP techniques and machine learning models.
