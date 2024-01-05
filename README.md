# Fine-tuning DistilBERT for Sentiment Analysis 

## Overview
This repository demonstrates the process of fine-tuning the DistilBERT model for sentiment analysis using the Hugging Face ecosystem. DistilBERT is a smaller, faster, cheaper, and lighter version of BERT, designed for resource-constrained environments.

## Key Concepts
- **DistilBERT**: A distilled version of the BERT model which retains most of its performance while being more efficient.
- **Hugging Face Ecosystem**: Provides tools and libraries for working with state-of-the-art machine learning models, especially in the field of natural language processing (NLP).
- **Sentiment Analysis**: The task of classifying the polarity of a given text as positive or negative.

## Data and Preprocessing
- The IMDb dataset is used for training and evaluation. It consists of movie reviews labeled as positive or negative.
- A subset of this dataset (1000 training samples and 100 test samples) is used to fine-tune the model.
- Preprocessing involves tokenizing the text data using the DistilBERT tokenizer.

## Model Training
- DistilBERT pre-trained on the 'distilbert-base-uncased' model is fine-tuned for sequence classification with two labels (positive and negative).
- Training configurations include learning rate, batch size, number of epochs, and weight decay.
- The model is evaluated using accuracy and F1 score metrics.

## Hugging Face Hub Integration
- The model, along with its tokenizer, is pushed to the Hugging Face Hub for easy sharing and collaboration.
- Users can access and use the fine-tuned model directly from the Hugging Face Hub.

## Usage
- The fine-tuned model can be used for sentiment analysis on new text data.
- The model classifies the sentiment of the input text as positive or negative.

## Conclusion
This project highlights the effectiveness of DistilBERT for sentiment analysis tasks. It shows how a powerful model can be fine-tuned with a relatively small dataset, leveraging the Hugging Face tools for training, evaluation, and deployment.

---

Note: This README provides a high-level overview of the project. The actual code is available in the repository.
