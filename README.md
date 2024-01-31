# Text Emotion Detection using NLP Techniques

## Overview

This repository contains code for text emotion detection using Natural Language Processing (NLP) techniques. The implementation includes data loading, text preprocessing, feature engineering, model training, and explanatory analysis. The code uses various models, including logistic regression and naive Bayes classifiers, along with pre-trained models like DistilBERT and ALBERT.

## Data

The emotion dataset is sourced from [Kaggle](https://www.kaggle.com/praveengovi/emotions-dataset-for-nlp) and comprises training, testing, and validation sets. Emotions are converted into binary labels: "not-stressed," "medium-stressed," and "stressed."

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/your-repo.git


## Install the required dependencies:
pip install -r requirements.txt


## Run the Jupyter notebook:
jupyter notebook



# Code Structure

- `data/`: Contains the emotion dataset.
- `notebooks/`: Jupyter notebooks for data loading, preprocessing, and model training.
- `src/`: Source code files for utility functions.
- `README.md`: Project overview and usage guide.

# Usage

1. Load and explore the dataset by running the `Data Loading and Exploration.ipynb` notebook.
2. Perform text preprocessing and feature engineering using `Text Preprocessing and Feature Engineering.ipynb`.
3. Train and evaluate models with `Model Training and Evaluation.ipynb`.
4. Explore additional analyses in relevant notebooks.

# Results

- Logistic Regression Accuracy: XX%
- Bernoulli Naive Bayes Accuracy: XX%
- Multinomial Naive Bayes Accuracy: XX%

# Model Explanations

- View top positive and negative features for logistic regression, BernoulliNB, and MultinomialNB in respective sections of the code.

# Additional Analyses

- POS Tagging
- N-grams
- BERT Model Usage

# Acknowledgments

- The dataset is sourced from Kaggle.

# License

This project is licensed under the MIT License.
