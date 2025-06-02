# Sentiment Analysis with Recurrent Neural Networks (RNN)

This project performs sentiment analysis on customer reviews using a Recurrent Neural Network (RNN). The goal is to classify reviews as positive or negative based on their textual content.

## Project Overview

- **Dataset:** Customer reviews with corresponding ratings.
- **Preprocessing:** Text cleaning, tokenization, and padding of sequences.
- **Model:** Sequential RNN model with an Embedding layer, SimpleRNN layer, and Dense output layer.
- **Training:** The dataset is split into training, validation, and test sets.
- **Output:** Binary sentiment classification (positive or negative).

## Dataset

The dataset contains customer reviews and their average ratings. Reviews are labeled as:
- **Positive (1):** Ratings greater than 3.5
- **Negative (0):** Ratings less than or equal to 3.5

*Note:* The dataset file should be named `swiggy.csv` and placed in the project directory.

## Preprocessing

- Convert reviews to lowercase.
- Remove punctuation and special characters.
- Tokenize reviews and convert them to sequences.
- Pad sequences to a fixed length for uniform input shape.

## Model Architecture

- Embedding layer to convert words into dense vectors.
- SimpleRNN layer to capture sequential dependencies.
- Dense layer with sigmoid activation for binary classification.

## How to Run

1. Ensure you have Python 3.x installed.
2. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn tensorflow
