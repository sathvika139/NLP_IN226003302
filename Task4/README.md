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