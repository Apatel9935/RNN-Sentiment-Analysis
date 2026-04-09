# 🧠 Sentiment Analysis using RNN (NLP Project)

## 📌 Overview

Sentiment Analysis is a Natural Language Processing (NLP) task that determines whether a piece of text expresses a positive or negative sentiment.

In this project, we build a **Recurrent Neural Network (RNN)** model using **PyTorch** to classify text reviews based on sentiment.

Recurrent Neural Networks are effective for sequence data as they capture context and dependencies between words in a sentence.

---

## 🎯 Objective

* To preprocess raw text data
* To convert text into numerical format
* To build and train an RNN model
* To classify reviews as **Positive** or **Negative**

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas & NumPy
* NLTK
* Scikit-learn
* PyTorch

---

## 📂 Project Workflow

### 1️⃣ Data Preprocessing

* Convert text to lowercase
* Remove URLs
* Remove punctuation
* Remove HTML tags
* Remove stopwords
* Apply stemming

---

### 2️⃣ Feature Extraction

* Used **TF-IDF Vectorization**
* Converted text into numerical vectors

---


### 4️⃣ Model Architecture

* Simple RNN layer
* Fully Connected Layer
* Sigmoid activation (Binary classification)

---

## 🧩 Model Details

```
Input → RNN Layer → Fully Connected Layer → Output
```

* Loss Function: Binary Cross Entropy (BCELoss)
* Optimizer: Adam
* Epochs: 10

---

## 📊 Results

* Model Accuracy: **~85.5%**
* Successfully classifies sentiment of text reviews

---


## 📈 Evaluation

* Used test dataset for evaluation
* Achieved good generalization performance

---


