# Fake News Detection with a Bi-directional LSTM in Keras

The purpose of this repository is to build and train a bidirectional LSTM in PyTorch in order to perform fake news classification. Before feeding a textual dataset into a sequence model (RNN, LSTM, BiLSTM, GRU, etc.), the text dataset needs to be converted to sequences of vectors which needs lots of preprocessing on the dataset. This repository shows all these required operations in a step-by-step procedure.

In summary, this repository performs the following operations:
1. Importing fake and real news datasets with Pandas and checking sizes and null values
2. Exploring the imported dataset and feature engineering
3. Performing data cleaning
4. Visualizing the cleaned dataset
5. Preparing the dataset for training by performing tokenization and padding
6. Build and train a bidirectional LSTM model
7. Evaluating the model performance
