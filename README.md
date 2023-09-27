# LSTM Text Generation

This repository contains a PyTorch implementation of a Long Short-Term Memory (LSTM) network for text generation. The model is trained on a given text dataset and can generate text sequences.

## Overview

- **Dataset**: The model is trained on a text dataset provided in the `anna.txt` file. This dataset is used to learn the patterns and language used in the text.

- **Model**: The LSTM-based text generation model is implemented using PyTorch. It takes a sequence of characters as input and predicts the next character in the sequence. The model architecture includes an LSTM layer and a fully connected layer.

- **Training**: The model is trained using the provided dataset. Cross-entropy loss is used as the training objective. Training is performed for a specified number of epochs.

- **Text Generation**: After training, the model can generate text sequences. You can provide an initial text prompt, and the model will continue the text based on the learned patterns.

