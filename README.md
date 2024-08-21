# Streaming-Tweet-Sentiment-Analysis 

## Overview
This project implements a real-time sentiment analysis system on streaming data, specifically Twitter data. The analysis pipeline leverages Apache Spark's structured streaming API to perform sentiment classification and MLflow for model tracking and evaluation. This notebook is designed for the Spring 2024 Final Project and aims to provide an end-to-end solution for streaming tweet sentiment classification.

## Features
Streaming Data Ingestion: Ingest tweets in real-time using Spark's structured streaming capabilities.
Preprocessing: Data cleaning, tokenization, and vectorization for text processing.
Model Training & Prediction: Real-time sentiment prediction using a machine learning model.
Evaluation: Accuracy, precision, recall, and F1-score calculations for model performance, with metrics logged using MLflow.
Visualization: Confusion matrix visualization stored as an MLflow artifact.



## Model Training:
The notebook applies BERT to classify the sentiment of the tweets.
The data is preprocessed, and the model is trained in real-time on the incoming tweet data.
The predictions are stored in a DataFrame for evaluation.

## Evaluation & Logging:
The model's performance is evaluated using accuracy, precision, recall, and F1-score.
All metrics are logged using MLflow for further analysis and tracking.
The confusion matrix of the results is stored as an artifact in MLflow.
