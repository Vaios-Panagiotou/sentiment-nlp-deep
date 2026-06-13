# sentiment-nlp-deep

Deep learning models for sentiment classification on Twitter data, implemented in PyTorch. This project contains the notebook developed for the *Artificial Intelligence II: Deep Learning for NLP* course.

## Features

- Custom preprocessing pipeline tailored for tweets
- Word embeddings using Word2Vec and pretrained vectors
- Neural architectures including CNNs, RNNs, and hybrid models
- Evaluation metrics: accuracy, precision, recall, and F1-score

## Contents

- `sentiment-nlp-deep.ipynb`: The main Jupyter notebook containing the complete pipeline:
  - **Data Loading & Preprocessing**: Handling Twitter-specific data, tokenization, and text cleaning.
  - **Word Embeddings**: Generation and application of Word2Vec representations.
  - **Model Architectures**: Definition of PyTorch models (CNN, RNN/LSTM, and hybrid approaches).
  - **Training & Evaluation**: Training loops, hyperparameter tuning, and performance metrics visualization.
- `requirements.txt`: Python dependencies required to run the project.

## Getting Started

```bash
git clone https://github.com/Alphawastaken/sentiment-nlp-deep.git
cd sentiment-nlp-deep
python -m venv venv
source venv/bin/activate   # Linux/macOS
# venv\Scripts\activate    # Windows
pip install -r requirements.txt


