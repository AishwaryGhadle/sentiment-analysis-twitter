# 💬 Sentiment Analysis using Deep Learning

## 📌 Overview

This project implements a sentiment analysis model using deep learning techniques to classify tweets as positive or negative.

## 🔧 Technologies Used
- Python  
- TensorFlow / Keras  
- NLTK  
- Scikit-learn  
- NumPy / Pandas   
---

## ❗ Problem Statement

To build a sentiment analysis model on Twitter data using deep learning techniques.

---

## 📊 Dataset

* Source: Kaggle Sentiment140 Dataset
* Dataset Link: https://www.kaggle.com/datasets/kazanova/sentiment140

**Details:**

* 1.6 million tweets
* Labels: Positive, Negative

---

## ⚙️ Methodology

### Data Preprocessing

* Text cleaning (removing URLs, symbols, stopwords)
* Tokenization
* Padding sequences

### Model

* Deep Learning model (LSTM / RNN / ANN)

### Training

* Loss Function: Binary Crossentropy
* Optimizer: Adam

---

## 📈 Results
- Model successfully classifies sentiment into positive and negative categories  
- Demonstrates effective text pattern recognition  

**Real-world impact:**  
Useful for analyzing customer feedback and product reviews.

---

## 🧪 Example Predictions

```
Input: "The product quality is amazing!"
Output: Positive

Input: "Very bad service and disappointing experience"
Output: Negative
```

---

## 🚀 How to Run

```bash id="h5s9m1"
git clone https://github.com/AishwaryGhadle/sentiment-analysis-twitter.git
cd sentiment-analysis-twitter
pip install -r requirements.txt
jupyter notebook
```

Open:

```bash id="5iz1px"
sentiment_analysis.ipynb
```

---

## 📁 Project Structure

```bash id="q6l2l1"
sentiment-analysis-twitter/
│
├── sentiment_analysis.ipynb
├── README.md
├── requirements.txt
```

---

## 📌 Future Improvements

* Use advanced models (BERT, Transformers)
* Improve preprocessing pipeline
* Deploy as web application

---

## 📜 License

MIT License

---

## 👤 Author

**Aishwary Ghadle**



