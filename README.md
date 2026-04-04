# NLP – Task 1

# NLP Processing Engine

## 📌 Overview

This project implements a robust NLP preprocessing pipeline to clean and transform noisy real-world text into structured tokens.

## ⚙️ Features

* Lowercasing
* Removal of numbers, URLs, and extra spaces
* Handling repeated characters
* Token filtering (removes short words except "no", "not")
* Noise reduction (emojis, symbols)

## 🧪 Testing

Tested on diverse inputs including:

* Emojis
* Slang
* URLs
* Repeated characters
* Mixed-case text

## 📊 Outputs

* Cleaned tokens
* Processed sentences
* Token analytics (count, uniqueness, avg length)
* Word frequency analysis
---


# NLP – Task 2

# 🧠 Sentiment Analysis using NLP & Machine Learning

## 📌 Overview

This project focuses on building an end-to-end Sentiment Analysis system using Natural Language Processing (NLP) techniques and multiple Machine Learning models. The goal is to classify text reviews into sentiment categories such as Positive, Negative, and Neutral.


## 📊 Dataset

* **Name:** Amazon Fine Food Reviews
* **Source:** https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews
* The dataset contains customer reviews along with ratings (1–5).
* Ratings were converted into sentiment labels:

  * 1–2 → Negative
  * 3 → Neutral
  * 4–5 → Positive

> Note: Dataset is not included in this repository due to size limitations.


## 🔧 NLP Pipeline

* Lowercasing text
* Removing punctuation & special characters
* Removing stopwords
* Tokenization
* Stemming

## ⚙️ Feature Engineering

* Bag of Words (BoW)
* TF-IDF (used for final model training)

## 🤖 Models Used

* Logistic Regression
* Naive Bayes
* Decision Tree
* Random Forest

## 📈 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score

## 📊 Results & Insights

* Logistic Regression performed best overall
* TF-IDF outperformed Bag of Words
* Naive Bayes was fastest but slightly less accurate
* Tree-based models showed signs of overfitting

## 🚀 Conclusion

TF-IDF combined with Logistic Regression provided the best performance for this sentiment classification task. Proper preprocessing significantly improved model accuracy.

## 📁 Project Structure

```
Task2/
 ├── sentiment_analysis.ipynb
 └── README.md
```

# NLP - Task 3

# 🤖 NLP Chatbot using Hugging Face Transformers

## 📌 Overview
This project is a simple chatbot built using a pre-trained transformer model from Hugging Face.  
It can interact with users and generate human-like responses in real time.

## 🚀 Features
- Conversational chatbot
- Uses pre-trained transformer model (DialoGPT / BlenderBot)
- Generates dynamic responses
- Continuous interaction until exit

## 🛠 Technologies Used
- Python
- Hugging Face Transformers
- PyTorch

## 📖 Conclusion
This project demonstrates how transformer models can be used to build simple conversational AI systems.

---

# NLP - Task 4

# BERT Fine-Tuning for Sentiment Analysis

## 📌 Project Overview
This project focuses on fine-tuning a BERT model for sentiment classification using the IMDB dataset.

## 🛠️ Technologies Used
- Python
- Hugging Face Transformers
- PyTorch
- Scikit-learn

## 📊 Dataset
IMDB Movie Reviews Dataset (Binary Sentiment Classification)

## ⚙️ Approach
- Data preprocessing and cleaning
- Tokenization using bert-base-uncased
- Fine-tuning BERT for classification
- Experimentation with:
  - Full fine-tuning
  - Freezing BERT layers
  - Fine-tuning last 2 layers

## 📈 Results

| Model Type        | Accuracy | F1 Score |
|------------------|---------|----------|
| Full BERT        | 0.818   | 0.819    |
| Frozen BERT      | 0.822   | 0.825    |
| Last 2 Layers    | 0.818   | 0.831    |

## 🧠 Key Insights
- Frozen BERT performed well due to strong pre-trained features
- Partial fine-tuning improved F1 score
- Full fine-tuning requires more training time for better performance

## 🚀 Conclusion
BERT is highly effective for NLP tasks. Partial fine-tuning offers a good trade-off between performance and computational efficiency.

---

# NLP - Task 5

# NLP Task 5 – Token Classification (POS Tagging & Chunking)

## 📌 Overview

This project focuses on fine-tuning a transformer model to perform **Part-of-Speech (POS) Tagging** and **Chunking** using token classification techniques.

## 🛠️ Tech Stack

* Python
* Hugging Face Transformers
* Datasets Library
* PyTorch

## 📊 Dataset

* CoNLL-2003 dataset
* Used for POS tagging and chunking tasks

## ⚙️ Model

* BERT (bert-base-uncased)
* Fine-tuned using Hugging Face Trainer

## 🚀 Workflow

Raw Data → Tokenization → Label Alignment → Model Training → Evaluation → Inference

## 📈 Results

* Evaluated using Precision, Recall, and F1-score
* Model successfully performs sequence labeling tasks

## 🔍 Key Learnings

* Token classification using transformers
* Handling subword tokenization & label alignment
* Difference between POS tagging and chunking
* Model training and evaluation using Trainer API
---
