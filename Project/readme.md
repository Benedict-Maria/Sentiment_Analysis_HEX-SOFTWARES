This project presents a complete implementation of Sentiment Analysis using Natural Language Processing (NLP) and Machine Learning techniques to classify text data into positive, negative, or neutral sentiment categories. Sentiment analysis is widely used across industries to understand customer feedback, public opinion, and social media behavior. This project demonstrates how raw text data can be transformed into meaningful insights through data preprocessing, feature engineering, and model building.

The dataset used contains multiple features, including:

textID – Unique identifier for each record

text – The main tweet or user-generated content

sentiment – The sentiment label (positive/negative/neutral)

Time of Tweet – Timestamp of the post

Age of User – Age of the user

Country – User’s country

Population-2020, Land Area, Density – Additional demographic and geographic attributes

While the dataset includes rich metadata, the core machine learning model focuses primarily on the text and sentiment columns, as they directly support the sentiment classification task. However, the additional fields are explored for statistical insights and visualizations to understand regional or demographic sentiment patterns.

The project workflow includes several key stages:

Data Loading: The CSV dataset is uploaded into Google Colab for processing.

Data Cleaning: Missing values, text inconsistencies, and data types are handled appropriately.

Text Preprocessing: Using NLTK, the text undergoes lowercasing, stopword removal, tokenization, and stemming to normalize the content.

Feature Extraction: TF-IDF Vectorization transforms processed text into numerical features suitable for machine learning models.

Model Training: A Logistic Regression model is trained to classify sentiment labels with efficient performance.

Evaluation: Model accuracy, classification reports, and confusion matrices are used to assess performance.

User Input Prediction: A custom input system is implemented so users can enter text and receive real-time sentiment predictions.

This repository provides a clear, beginner-friendly example of how to perform sentiment classification using Python, making it valuable for students, interns, and developers exploring sentiment analysis or NLP-based machine learning projects.
