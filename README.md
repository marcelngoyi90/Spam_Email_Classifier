# Spam Email Classifier

An NLP classification project that detects whether an email is spam or ham using text preprocessing, vectorization, and a Multinomial Naive Bayes classifier.

## Project Overview

This project demonstrates a complete text-classification workflow: dataset exploration, preprocessing, Bag-of-Words vectorization, model training, and evaluation with standard classification metrics.

## Dataset

The repository includes `emails.csv` for learning and demonstration purposes.

| Column | Description |
|---|---|
| `text` | Email message content |
| `spam` | Target label: `1` = spam, `0` = ham |

## Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Methodology

1. Load and inspect the email dataset.
2. Explore class distribution between spam and ham messages.
3. Transform raw email text into numerical features with `CountVectorizer`.
4. Train a Multinomial Naive Bayes classifier.
5. Evaluate predictions using accuracy, precision, recall, F1-score, and a confusion matrix.

## Why Naive Bayes?

Multinomial Naive Bayes is a strong baseline for text classification because it works well with word-count features and is fast to train. This makes it useful for spam filtering, sentiment analysis, and other document classification tasks.

## How to Run

```bash
git clone https://github.com/marcelngoyi90/Spam_Email_Classifier.git
cd Spam_Email_Classifier
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook
```

Open the notebook and run the cells from top to bottom.

## Future Improvements

- Compare Bag-of-Words with TF-IDF features.
- Add a simple Streamlit demo for email classification.
- Save the trained model and vectorizer for reuse.
- Add tests for the text preprocessing pipeline.
