# multilingual-sentiment-analysis

# Multilingual Sentiment Analysis System

![Language Diversity](https://img.shields.io/badge/Languages-English%20%7C%20Urdu%20%7C%20More-blue)

## Overview
This project demonstrates a **multilingual sentiment analysis model** capable of classifying text sentiment (positive, negative, neutral) in multiple languages including English and Roman Urdu.  
It leverages state-of-the-art **transformers** for training and provides an interactive **Gradio app** for real-time predictions.

## Features
- Supports **code-mixed** and romanized Urdu text
- Utilizes pretrained multilingual models like `xlm-roberta-base`
- Uses advanced preprocessing techniques for cleaning and normalization
- Includes deep learning model training with Hugging Face Transformers
- Deploys an interactive UI with Gradio for easy use
- Implements best practices: stratified splitting, class weighting, early stopping

## Dataset
- The dataset contains thousands of labeled sentences in English and Roman Urdu.
- Data source: [Provide source or your collected data details]

## Getting Started

### Installation
```bash
git clone https://github.com/yourusername/multilingual-sentiment-analysis.git
cd multilingual-sentiment-analysis
pip install -r requirements.txt


Usage
Run training notebook to fine-tune the model (notebooks/part_a_training.ipynb)

Deploy with Gradio app (notebooks/part_b_gradio_deployment.ipynb)

Results
Achieved around 74% accuracy on test data

Confusion matrix and classification reports included in notebooks

Demo
Try the live demo on Google Colab with Gradio [Insert link if public]

License
MIT License
