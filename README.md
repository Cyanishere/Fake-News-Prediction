# Fake News Prediction Project

## Overview
News Fake nowadays are everywhere. To aviod being manipulated and controlled by Fake News, I build a simple fake news predictor. It ccurately classify a piece of news as REAL or FAKE.

## Technical Aspect
Train the model using two algorithms:
TF (Term Frequency): This measures how often a word appears in a document. A higher Term Frequency indicates that the term is more prevalent, suggesting that the document is a strong match when the term is included in the search query.

IDF (Inverse Document Frequency): This assesses the significance of a term across the entire corpus. Terms that appear frequently in many documents may be less relevant, and IDF helps to quantify this by measuring their uniqueness.

The TfidfVectorizer transforms a collection of raw documents into a matrix of TF-IDF features, enabling effective representation for various analytical tasks.

## Installation
The Code is written in Python 3.12.11 (Google Colab).
To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```


