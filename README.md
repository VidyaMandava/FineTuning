# Sentiment Analysis using Prompt Tuning

## Overview
This project demonstrates **Prompt Tuning** for sentiment analysis on **Amazon Product Reviews** using a **lightweight Hugging Face model**. The model classifies reviews as **Positive** or **Negative** .

## Features
- **Fine-tuned Model:** Uses Prompt Tuning for efficient adaptation.
- **Zero-shot vs Fine-tuned Accuracy:** Evaluates improvement through fine-tuning.
- **Performance Metrics:** Precision, Recall, and F1-score analysis.
- **Optimized for Colab:** Runs efficiently with limited GPU resources.

## Dataset
We used a subset of the **Amazon Product Reviews** dataset, containing reviews labeled as **Positive** or **Negative**.

## Model Training
- **Base Model:** `distilbert-base-uncased`
- **Fine-tuning Method:** **Prompt Tuning**
- **Trainable Parameters:** Reduced to ~10k to optimize training efficiency.
- **Framework:** `Hugging Face Transformers + PEFT`
- **Environment:** Google Colab with limited GPU resources.

## License
This project is licensed under the MIT License.

