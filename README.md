# Emotion Classification and Sentiment Analysis

This project performs **emotion classification** and **sentiment analysis** on text data using machine learning. It predicts emotions (e.g., happiness, sadness, anger) and sentiment (positive, negative, neutral) for input text.

## Features
- Emotion classification (e.g., happiness, sadness, anger).
- Sentiment analysis (positive, negative, neutral).
- Easy-to-use for predictions.

## Installation
. Clone the repository:
   
   git clone https://github.com/siddhxrth7/emotion-classification-sentiment-analysis.git
   cd emotion-classification-sentiment-analysis

# Usage
Train the model using your dataset.

Predict emotions and sentiment for new text inputs:

python :

text = "I am feeling so happy today!"
emotion = model.predict_emotion(text)
sentiment = model.predict_sentiment(text)
print(f"Emotion: {emotion}, Sentiment: {sentiment}")
