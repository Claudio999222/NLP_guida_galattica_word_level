# NLP_Galactic_Guide_Word_Level

## Overview

This notebook explores Natural Language Processing (NLP) techniques using the "Hitchhiker's Guide to the Galaxy" trilogy as a dataset. Unlike the previous character-level LSTM model, this notebook focuses on training a word-level LSTM model. The goal is to generate new text based on the patterns learned at the word level in the input data.

## Key Components:

1. **Dataset Preparation**: Load and preprocess the text data from the "Hitchhiker's Guide to the Galaxy" trilogy. Convert the text into a format suitable for training an LSTM model at the word level.

2. **Word-Level LSTM Model**: Define the architecture of the LSTM model that operates at the word level. Configure the model with appropriate parameters such as the number of LSTM units, dropout, and activation functions.

3. **Training the Model**: Train the word-level LSTM model on the prepared dataset. Utilize Keras callbacks for better training results and set a lower epsilon in the architecture to prevent division by zero during training.

4. **Generating Text**: Use the trained model to generate new text. Given a seed sequence of words, the model predicts the next words, and this process is iteratively repeated to generate a sequence of words.

## Why Word-Level LSTM?

- **Semantic Understanding**: A word-level LSTM model captures semantic meaning at a higher level compared to character-level models. This is beneficial for tasks where understanding word relationships is essential.

- **Higher-Level Context**: Word-level models can generate text with a focus on higher-level context, making them suitable for tasks such as sentence or paragraph generation.

- **Improved Readability**: Text generated at the word level tends to have better readability and coherence compared to character-level text.

This notebook serves as a demonstration of applying NLP techniques, specifically word-level LSTM, to generate text based on the content of the "Hitchhiker's Guide to the Galaxy" trilogy.
