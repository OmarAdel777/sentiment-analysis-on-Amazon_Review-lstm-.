# Sentiment Analysis with LSTM

This project aims to perform sentiment analysis on text data using Long Short-Term Memory (LSTM) networks. Sentiment analysis is a natural language processing task that involves determining the sentiment expressed in a piece of text, such as whether the text expresses a positive or negative sentiment.

## Dataset

The dataset used in this project is the Amazon Reviews dataset, which consists of reviews from Amazon customers. The reviews are labeled as either positive or negative.

## Preprocessing

Before training the LSTM model, the text data is preprocessed in the following steps:

1. **Data Loading**: The dataset is loaded from the provided files.
2. **Tokenization and Padding**: The text data is tokenized into sequences of integers and padded to ensure uniform sequence lengths.

## Model Architecture

The LSTM model architecture is as follows:

- **Embedding Layer**: Maps each word index to a dense vector representation.
- **LSTM Layers**: One or more LSTM layers to capture sequential patterns in the data.
- **Dense Layer**: A dense layer with a sigmoid activation function for binary classification.

## Training

The model is trained using different configurations, including different optimizers, activation functions, and LSTM layer configurations. Each configuration is trained for 5 epochs with a batch size of 2048.

## Results

The results of each model configuration are evaluated in terms of loss and accuracy on a separate test set. The configurations and their corresponding performance metrics are presented at the end of the training process.

## Usage

To train the model:

1. Ensure you have the necessary dependencies installed (see `requirements.txt`).
2. Run the training script `train.py`.

## Requirements

- Python 3.x
- TensorFlow (version x.x.x)
- Keras (version x.x.x)
- NumPy
- Pandas

## Credits

This project was developed by Eng/ Omar Adel. It is based on the Amazon Reviews dataset and utilizes the TensorFlow and Keras libraries for deep learning.
