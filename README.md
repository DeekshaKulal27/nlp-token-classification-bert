# 🧠 BERT for POS Tagging & Chunking (Token Classification)

## 📌 Project Overview

This project focuses on building and fine-tuning a Transformer-based
model (DistilBERT) to perform Token Classification tasks such as: -
Part-of-Speech (POS) Tagging\
- Chunking (Phrase Detection)

## 🎯 Objective

-   Understand token classification using transformer models\
-   Perform POS tagging and chunking\
-   Handle tokenization and label alignment\
-   Evaluate model performance

## 🛠️ Technologies Used

Python, Hugging Face Transformers, PyTorch, Google Colab

## 📊 Dataset

Kaggle NER Dataset (CoNLL-style format)

## 🔄 Workflow

Dataset → Tokenization → Label Alignment → Training → Evaluation →
Inference

## ⚙️ Model

DistilBERT (distilbert-base-uncased)

## 📈 Evaluation

Precision: 0.87\
Recall: 0.85\
F1 Score: 0.86

## 🔍 Example

Input: John works at Google in California

Output: John → B-PER\
Google → B-ORG\
California → B-LOC

## 🙏 Acknowledgment

Innomatics Research Labs

## 📌 Author

Deeksha
