# Hate Speech Classification 🧠📱

This project tackles the important problem of identifying hate speech in social media text using deep learning models. We leverage Recurrent Neural Networks (RNNs) and modern NLP techniques to build robust classifiers capable of detecting hateful content.

## 🔍 Project Overview

The aim is to classify tweets into:
- **Hateful**
- **Offensive**
- **Neither**

This classification task is part of a broader effort to combat online abuse and improve social media moderation systems.

## 📁 Repository Structure

```
Hate_Speech_Classification/
│
├── Hate_Speech_Classification_Task1.ipynb          # Data preprocessing, EDA, and traditional models
├── Hate_Speech_Classification_using_RNNs.ipynb     # RNN-based model implementation (LSTM, GRU)
└── README.md                                        # Project documentation
```

## 📊 Dataset

The dataset contains 25,000+ tweets labeled as:
- **0**: Hate Speech
- **1**: Offensive Language
- **2**: Neither

## ⚙️ Features & Techniques

### In `Hate_Speech_Classification_Task1.ipynb`:
- Data cleaning (removal of URLs, mentions, emojis, etc.)
- Exploratory Data Analysis (word clouds, label distribution, tweet lengths)
- Vectorization using TF-IDF
- Classifiers: Logistic Regression, Naive Bayes, SVM, etc.

### In `Hate_Speech_Classification_using_RNNs.ipynb`:
- Tokenization & Padding
- Embedding Layer
- RNN Architectures:
  - LSTM
  - GRU
- Model evaluation using accuracy, precision, recall, and confusion matrix

## 📈 Results

The RNN-based models showed significant improvement over traditional machine learning classifiers in capturing the sequential nature and context of tweets, leading to better classification performance.

## 🛠️ Requirements

Install dependencies with:

```bash
pip install -r requirements.txt
```

Or manually ensure the following are installed:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `nltk`
- `tensorflow` or `keras`

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/mohamedsalama677/Hate_Speech_Classification.git
cd Hate_Speech_Classification
```

2. Open the notebooks in Jupyter or VS Code.
3. Run all cells step by step to reproduce results.

## 🙌 Acknowledgments

Thanks to the open-source community and dataset contributors who made this project possible.
