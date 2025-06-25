# LSTM_model

# LSTM for Next-Word Prediction with PyTorch

This project is a simple implementation of a Long Short-Term Memory (LSTM) network for next-word prediction. The model is built using PyTorch and trained on a subset of the BookCorpus dataset.

## Project Overview

The goal of this project is to build a language model that, given a sequence of words, can predict the most likely next word.

### How It Works

1.  **Data Loading**: A subset of the BookCorpus dataset is loaded.
2.  **Preprocessing**: The text is tokenized, and a vocabulary is built.
3.  **Sequence Preparation**: The text is broken down into input sequences and target words.
4.  **Model Architecture**: The model uses Embedding, LSTM, and Linear layers.
5.  **Training**: The model is trained to predict the next word in a sequence.
6.  **Inference**: A function generates new text by repeatedly predicting the next word.

## Setup and Installation

To run this project, you will need Python 3 and Git installed.

**1. Clone the repository:**
```bash
git clone https://github.com/rishu1947-ops/LSTM_model.git
cd LSTM_model
