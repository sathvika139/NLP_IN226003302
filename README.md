# NLP Preprocessing Engine – Task 1

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


# NLP Preprocessing Engine – Task 2

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
