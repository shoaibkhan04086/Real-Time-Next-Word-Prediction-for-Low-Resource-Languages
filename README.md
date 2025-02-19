# Real-Time Next-Word Prediction for Low-Resource Languages

## Project Overview

This project focuses on **next-word prediction** for **low-resource languages**, specifically targeting **Hinglish (Hindi-English code-mixed)** datasets. The goal is to create a robust solution for predicting the next word in real-time, tailored to handle the challenges posed by multilingual and code-mixed text.

Low-resource languages often lack extensive datasets, making traditional NLP approaches less effective. This project provides a scalable and efficient framework for enhancing text prediction capabilities for such languages. The model utilizes **LSTM (Long Short-Term Memory)** networks to predict the next word in a sequence, trained on a **Hinglish** dataset to capture the intricacies of code-mixing between Hindi and English.

The application of this model is aimed at improving real-time text prediction in chatbots, virtual assistants, and other real-time applications in low-resource languages.


### Features:
- Trained using a dataset of Sherlock Holmes stories.
- Uses **LSTM** for handling sequential data and generating predictions.
- Predicts the next word based on the given input text.

## Import libraries

Before running the project, you need to have Python installed on your system. You can also work on google collab :

- import numpy as np
- import tensorflow as tf
- from tensorflow.keras.preprocessing.text import Tokenizer
- from tensorflow.keras.preprocessing.sequence import pad_sequences
- from tensorflow.keras.models import Sequential
- from tensorflow.keras.layers import Embedding, LSTM, Dense
- from tensorflow.keras.utils import to_categorical


