# Sentiment Analysis Project

This project showcases sentiment analysis on the Amazon Fine Food Reviews dataset using Python. The objective was to classify sentiments as positive, negative, or neutral, utilizing different techniques.

## Features

1. **VADER Sentiment Analysis (Bag of Words Approach):**
   I started with VADER, a lexicon and rule-based sentiment analysis tool, using a bag-of-words approach. This provided initial insights into the dataset's sentiment distribution.

2. **RoBERTa Pretrained Model from 🤗 (Hugging Face):**
   To enhance accuracy, I fine-tuned a RoBERTa pre-trained model from 🤗. This deep learning approach improved sentiment classification performance.

3. **Huggingface Pipeline:**
   Leveraging Hugging Face's Pipeline, I streamlined the sentiment analysis process. This allowed for easy and efficient sentiment predictions using the trained model.

## Dataset

I utilized the [Amazon Fine Food Reviews dataset](https://www.kaggle.com/snap/amazon-fine-food-reviews) from Kaggle. This dataset contains a collection of food reviews, which I employed to train and evaluate the sentiment analysis models.

## Project Structure

- `data/`: This directory contains the dataset (not included in this repository).
- `notebooks/`: Jupyter notebooks illustrating each step of the project.
- `src/`: Python scripts for preprocessing, model training, and evaluation.
- `results/`: Visualizations and model performance metrics.

## Usage

1. Clone this repository: `git clone https://github.com/your-username/sentiment-analysis-project.git`
2. Navigate to the `notebooks/` directory to follow the project's flow.
3. Experiment with different models and techniques using the provided scripts in the `src/` directory.

Feel free to reach out for questions or suggestions!

## Acknowledgments

I'd like to express gratitude to the creators of VADER, 🤗 RoBERTa, and Hugging Face for their valuable tools and resources.
