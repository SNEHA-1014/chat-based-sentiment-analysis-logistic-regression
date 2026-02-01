# Chat-Based Sentiment Analysis using Logistic Regression

This project implements a chat-based sentiment analysis system that classifies text messages into **Positive**, **Negative**, or **Neutral** sentiments using Machine Learning.

## 🚀 Features
- Text preprocessing and cleaning
- TF-IDF feature extraction (word + character n-grams)
- Logistic Regression classifier
- Class balancing using SMOTE
- Evaluation using accuracy, precision, recall, F1-score
- Confusion matrix and performance visualizations
- Real-time sentiment prediction
- Model persistence using joblib

## 📊 Dataset
The dataset contains chat-style messages with sentiment labels:
- **TEXT** – Chat message
- **REACTION** – Sentiment label (positive, negative, neutral)

## 🧠 Model Used
- Logistic Regression
- TF-IDF Vectorization
- SMOTE for class imbalance handling

## 📈 Results
- Accuracy: ~77%
- Balanced performance across all sentiment classes

## 📁 Project Structure
