# Fake News Detection Using NLP and BERT

## Project Overview

This project focuses on detecting whether a news article is **Fake** or **Real** using Natural Language Processing (NLP), Machine Learning, Deep Learning, and Transformer-based models.

The project compares multiple approaches including TF-IDF + SVM, Word2Vec + LSTM, and BERT to identify the most effective model for fake news classification.

---

## Dataset

**Dataset Source:** Kaggle - Fake and Real News Dataset

Dataset Files:

* Fake.csv
* True.csv

Total Records: 44,898

---

## Technologies Used

* Python
* Pandas
* NumPy
* NLTK
* Scikit-Learn
* TensorFlow / Keras
* PyTorch
* Hugging Face Transformers
* Gradio
* Matplotlib
* Seaborn

---

## Project Workflow

Dataset Collection
→ Data Cleaning
→ Exploratory Data Analysis
→ WordCloud Visualization
→ TF-IDF Feature Extraction
→ SVM Classification
→ Word2Vec Embedding
→ LSTM Classification
→ BERT Fine-Tuning
→ Model Comparison
→ Confusion Matrix
→ Classification Report
→ Gradio User Interface

---

## Data Preprocessing

The following preprocessing steps were performed:

* Lowercase conversion
* URL removal
* Special character removal
* Stopword removal
* Text cleaning

---

## Models Implemented

### 1. TF-IDF + SVM

Accuracy Achieved: **99.36%**

### 2. Word2Vec + LSTM

Used Word2Vec embeddings and LSTM architecture for sequence learning.

### 3. BERT (Transformer)

Fine-tuned BERT model using Hugging Face Transformers.

Accuracy Achieved: **99.75%**

Validation Loss: **0.0208**

---

## Model Comparison

| Model | NLP Technique | Accuracy                 |
| ----- | ------------- | ------------------------ |
| SVM   | TF-IDF        | 99.36%                   |
| LSTM  | Word2Vec      | Obtained during training |
| BERT  | Transformer   | 99.75%                   |

---

## Results

### Best Performing Model

**BERT**

Reasons:

* Highest Accuracy
* Lowest Validation Loss
* Better Context Understanding
* Excellent Generalization

---

## User Interface

A Gradio-based user interface was developed to classify news articles in real time.

Features:

* Enter News Article
* Click Predict
* Get Fake News / Real News Prediction

---

## Future Enhancements

* Explainable AI using SHAP
* Real-Time News Verification
* Multilingual Fake News Detection
* Cloud Deployment
* Mobile Application Integration

---

## Internship Requirements Covered

* Kaggle Dataset ✔
* TF-IDF ✔
* Word2Vec ✔
* BERT ✔
* SVM ✔
* LSTM ✔
* Fake News Classification ✔

Additional Features:

* EDA
* WordCloud
* Model Comparison
* Confusion Matrix
* Classification Report
* Gradio UI

---

## Author

Brunda P

M.Sc. Data Science
