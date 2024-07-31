# Sentiment_Analysis-of-IMDB_Review
Recurrent Neural Network (RNN) with LSTM for Binary Text Classification
Overview
This project implements an LSTM-based Recurrent Neural Network (RNN) for binary text classification. It is designed for tasks like sentiment analysis where the goal is to classify text data into two categories, such as positive or negative sentiment. The model processes textual data by leveraging Long Short-Term Memory (LSTM) units to capture contextual information and long-term dependencies, which enhances its ability to understand and classify complex text patterns.

**Key Features**

**1) Data Processing:**
   
Tokenization: Splits text into words or tokens.

Padding: Ensures all sequences have the same length for consistent input.

Text Embedding: Converts words into numerical vectors using an embedding layer.

**2)Model Architecture:**

Embedding Layer: Transforms tokenized words into dense vectors of fixed size.

LSTM Units: Captures long-term dependencies and context in sequences.

Dense Output Layer: Provides the final binary classification result (positive or negative).

**3)Model evaluation on Unseen Test Data:**

Accuracy: Measures the proportion of correctly classified instances.

Precision: Indicates the accuracy of positive predictions.

Recall: Measures the ability to find all positive instances.

F1-Score: Combines precision and recall into a single metric.

**4)Dataset Used:**

IMDB Movie Reviews: Used for training and evaluating the sentiment classification model.

**5)How to Use:**

Install dependencies: tensorflow, numpy, scikit-learn.

Prepare and preprocess data.

Train the model and evaluate its performance.


