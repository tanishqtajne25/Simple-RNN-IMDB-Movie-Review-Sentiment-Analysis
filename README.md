# Simple-RNN-IMDB-Movie-Review-Sentiment-Analysis
End to End project on Simple RNN on IMDB movie dataset sentiment classification
his project demonstrates a complete machine learning pipeline for natural language processing (NLP), from model training to a user-friendly web application. It classifies movie reviews from the IMDB dataset as either positive or negative using a simple Recurrent Neural Network (RNN).

The project is built using TensorFlow for the deep learning model and Streamlit for the interactive web interface, making it easy to see the model's predictions in real-time.

Features
Data Preprocessing: Handles raw text data by tokenizing and padding sequences to a uniform length.

Model Training: Trains a sequential model with an Embedding layer, a SimpleRNN layer, and a Dense output layer.

Early Stopping: Implements a callback to prevent overfitting and optimize training time.

Model Persistence: Saves the trained model to disk for later use, avoiding the need for retraining.

Interactive Web App: Provides a simple Streamlit interface where users can input a movie review and get an instant sentiment prediction.
