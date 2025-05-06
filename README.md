# AI_Text_Checker

# Enhancing AI-Generated Text Detection with Sentiment-Based Emotional Tone

This project investigates whether integrating emotional sentiment analysis into transformer-based models improves the detection of AI-generated text. It compares three models:
- **VADER Sentiment-Only Classifier**
- **BERT Transformer-Based Classifier**
- **Hybrid BERT + VADER Model**

## 📁 Project Files

- `llm_vader.ipynb`: Uses only VADER sentiment scores for detection.
- `llm_bert.ipynb`: Uses only BERT embeddings for text classification.
- `llm_vader_bert.ipynb`: Combines VADER sentiment and BERT embeddings for hybrid detection.
- `test.csv`, `test1.csv`, `test2.csv`: Sample datasets containing AI and human text.

---

## ⚙️ How to Run from Scratch (Full Setup Guide)

Follow these steps to run the project even if you're starting from a blank environment.

### 1. 🔧 Set Up Python Environment

First, make sure you have **Python 3.7 or above** installed.

It's recommended to use a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

### 2. Install Required Library

pip install pandas numpy scikit-learn vaderSentiment transformers torch matplotlib


 
