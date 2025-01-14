# Real-Time Next-Word Prediction for Low-Resource Languages
Overview
This project focuses on next-word prediction for low-resource languages, specifically targeting Hinglish (Hindi-English code-mixed) datasets. The goal is to create a robust solution for predicting the next word in real-time, tailored to handle the challenges posed by multilingual and code-mixed text.

Low-resource languages often lack extensive datasets, making traditional NLP approaches less effective. This project provides a scalable and efficient framework for enhancing text prediction capabilities for such languages.



## Table of Contents

1. [Project Overview](#project-overview)
2. [Installation Instructions](#installation-instructions)
3. [Usage](#usage)
4. [Model Architecture](#model-architecture)
5. [Model Evaluation](#model-evaluation)
6. [License](#license)

## Project Overview

This project leverages **LSTM (Long Short-Term Memory)** networks for **Next-Word Prediction** on the Sherlock Holmes text dataset. The objective is to predict the next word in a given sentence or phrase. The model is trained on the dialogues and text from the Sherlock Holmes stories to capture the patterns and sequences in the language.

### Features:
- Trained using a dataset of Sherlock Holmes stories.
- Uses **LSTM** for handling sequential data and generating predictions.
- Predicts the next word based on the given input text.

## Installation Instructions

### Prerequisites

Before running the project, you need to have Python installed on your system. You also need to install the following Python libraries:

- `numpy`
- `pandas`
- `tensorflow`
- `nltk`
- `scikit-learn`

You can install the required dependencies by running the following:

```bash
pip install numpy pandas tensorflow nltk scikit-learn
