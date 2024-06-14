# SentimentAnalysisPytorch
Sentiment Analysis Using LSTM on the IMDB Dataset
This project aims to perform sentiment analysis using a Long Short-Term Memory (LSTM) network to classify movie reviews from the IMDB dataset. The dataset comprises 50,000 movie reviews labeled as either positive or negative, offering a balanced set for training and evaluation. The objective is to develop a deep learning model capable of accurately predicting the sentiment of a movie review.

Project Overview
1) Data Preprocessing:
The dataset undergoes preprocessing, which includes tokenizing the text reviews, removing special characters, and padding sequences to ensure uniform input lengths for the LSTM network.
A vocabulary is constructed from the training data to convert words into indices for embedding.

2) Model Architecture:
An LSTM network is utilized for its ability to capture long-term dependencies in sequential data, making it ideal for natural language processing tasks.
The model features an embedding layer, LSTM layers, dropout layers to prevent overfitting, and a fully connected layer with a sigmoid activation function to output the probability of a review being positive.

3) Training and Evaluation:
The model is trained using binary cross-entropy loss and optimized with the Adam optimizer.
Accuracy is the primary metric for evaluating performance on both the training and validation sets.
Gradient clipping is applied during training to prevent the exploding gradient problem, ensuring stable training of the LSTM network.

4) Results and Predictions:
The trained model can predict the sentiment of unseen movie reviews with high accuracy.
A function is provided to preprocess and predict the sentiment of custom reviews, demonstrating the model's practical application.
This project showcases the effectiveness of LSTM networks in handling sequential text data for sentiment analysis. Utilizing the IMDB dataset, it serves as a comprehensive example of building, training, and evaluating a deep learning model for binary sentiment classification.


