# Shakespeare Text Generator (LSTM)

## Overview
This project is a text generation model built using TensorFlow/Keras and trained on Shakespeare's works. It utilizes an LSTM architecture to predict the next word in a sequence.

## Architecture
* **Embedding Layer:** Vectorizes input tokens.
* **LSTM Layer:** 150 units for sequence processing.
* **Dense Layer:** Softmax activation for token prediction.

## Dataset
* Source: [Tiny Shakespeare](https://raw.githubusercontent.com/karpathy/char-rnn/master/data/tinyshakespeare/input.txt)
* Preprocessing: Lowercasing, punctuation removal, tokenization.

## How to Run
Open the `.ipynb` file in Google Colab or Jupyter Notebook and run all cells sequentially.
