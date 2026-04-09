# 📧 Email Spam Classifier

A machine learning project that classifies emails as **Spam** or **Not Spam** using **Google's Word2Vec embeddings** and a **Random Forest classifier** — implemented entirely in a Jupyter Notebook.

---

![Banner](https://github.com/ShivendraSinha418/Email-Spam-Classifier/blob/main/emailspam.png)

---
## 🧠 Overview

This project explores a more **context-aware** approach to spam detection. Instead of using TF-IDF or Bag-of-Words, it leverages **semantic word embeddings from Google’s Word2Vec model**, combined with a **Random Forest algorithm** to classify emails.

---

## 🚀 Features

- Implemented in a single Jupyter Notebook
- NLP-based text preprocessing
- Google Word2Vec (pre-trained) for word embeddings
- Vector averaging to represent entire emails
- Random Forest Classifier for prediction
- Evaluation metrics like accuracy, precision, recall, and F1-score

---

## 🛠️ Technologies Used

- Python 3.x
- Jupyter Notebook
- NLTK (text cleaning, stopword removal)
- Gensim (Word2Vec model loading)
- Scikit-learn (RandomForestClassifier & evaluation)

---

## 🔁 Workflow

1. **Text Preprocessing**
   - Lowercase conversion
   - Tokenization
   - Stopword removal
2. **Embedding**
   - Load Google's `GoogleNews-vectors-negative300` Word2Vec model
   - Convert each email into a 300-d vector by averaging word vectors
3. **Classification**
   - Train a **Random Forest classifier**
   - Use cross-validation & metrics to evaluate performance
4. **Prediction**
   - Input: Raw email text  
   - Output: **Spam** or **Not Spam**

---
