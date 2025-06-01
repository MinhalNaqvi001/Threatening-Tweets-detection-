# Threatening-Tweets-detection-
This is an NLP-based project focused on detecting threatening tweets in the Urdu language using transformer models
## 🔍 Project Overview

The goal was to build a binary text classification model that can identify whether an Urdu comment is:
- **Sensitive / Threatening (1)**
- **Non-Sensitive / Safe (0)**

To accomplish this, we fine-tuned the **XLM-RoBERTa** multilingual transformer model — capable of understanding various languages, including Urdu.

## 🚀 Technologies Used

- **Hugging Face Transformers**
- **XLM-RoBERTa Model**
- **Pandas**
- **Hugging Face Datasets**
- **Google Colab 

## 📁 Main Components

- `AutoTokenizer` – Tokenizes Urdu text into numerical inputs.
- `AutoModelForSequenceClassification` – Pre-trained model used for binary classification.
- `Trainer & TrainingArguments` – For model training and evaluation.
- Urdu dataset was loaded from Excel, converted to a Hugging Face dataset format.

## 📊 Results

The model successfully classifies tweets/comments into sensitive and non-sensitive categories. It shows promising performance in understanding and processing Urdu — a low-resource language in NLP.

## 🌍 Why It Matters

This project contributes to content moderation and digital safety for Urdu speakers — promoting responsible use of AI in underrepresented languages.

---

**Developed by:**
- Syed Muhammad Minhal Naqvi  

#NLP #Urdu #Transformers #HuggingFace #MachineLearning #ContentModeration
