# 🎬 IMDb Movie Sentiment Analyzer

An end-to-end IMDb movie sentiment analysis project using
Natural Language Processing, QLoRA fine-tuning, Hugging Face
Transformers, BERT and Gradio.

## 📌 Project Overview

This project explores sentiment classification on IMDb movie
reviews.

The project includes:

- IMDb dataset preparation
- QLoRA fine-tuning
- Qwen2.5-1.5B-Instruct model
- Sentiment evaluation
- Confusion matrix
- Classification report
- Interactive Gradio application

## 🧠 Project Workflow

IMDb Dataset
      ↓
Data Preparation
      ↓
QLoRA Fine-Tuning
      ↓
Qwen2.5-1.5B-Instruct
      ↓
Sentiment Evaluation
      ↓
Gradio Application

## 🤖 Model Training

The project uses:

**Qwen/Qwen2.5-1.5B-Instruct**

QLoRA is used to fine-tune the model using a smaller
computational footprint.

## 📊 Dataset

The project uses the Stanford IMDb movie review dataset.

The training workflow uses a selected subset of the dataset
for experimentation.

## 📈 Evaluation

The project includes:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Sample prediction testing

## 🎬 Gradio Application

The project includes an interactive movie sentiment analyzer.

Users can enter a movie review and receive:

- 😊 Positive sentiment
- 😞 Negative sentiment
- 📊 Confidence score

The interface is designed with a movie/cinema-inspired theme.

## 🛠️ Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- Hugging Face Datasets
- QLoRA
- PEFT
- TRL
- BitsAndBytes
- Scikit-learn
- Matplotlib
- Gradio
- Google Colab

## 📂 Project Structure

```text
IMDb-Movie-Sentiment-Analyzer/
│
├── IMDb_Movie_Sentiment_Analyzer.ipynb
├── requirements.txt
└── README.md
