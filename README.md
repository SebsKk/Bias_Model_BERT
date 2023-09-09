# Bias Classification Project

## Overview

This project aims to classify text into biased and unbiased categories. The project uses a machine learning model based on the Transformer architecture, particularly BERT (Bidirectional Encoder Representations from Transformers). 

## Data Collection

The dataset consists of a variety of biased and unbiased prompts. These prompts cover multiple topics and are generated using ChatGPT. The prompts are designed to exhibit various types of bias and are written in different styles.

## Data Preprocessing

1. The dataset was initially in a DataFrame format, containing columns for prompts and their corresponding biased and unbiased responses.
2. The data was tokenized and prepared for the model using the `Transformers` library.

## Model Training and Testing

1. The BERT model from the `Transformers` library was fine-tuned for the task of bias classification.
2. The model was trained and validated on the prepared dataset.
3. Performance metrics such as accuracy, precision, recall, and specificity were calculated to evaluate the model.

## Credits

The project largely follows the methodology described by Nicolo Cosimo Albanese in his article "Fine-Tuning BERT for Text Classification".

## Future Work

Classify biased text into more specific categories like cognitive, prejudice, contextual, and unconscious bias.




