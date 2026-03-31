# 📰 Fake News Detection using Machine Learning & NLP

## 📌 Overview
This project focuses on detecting fake vs real news articles using Natural Language Processing (NLP) and machine learning models. The goal is to build a robust classification system and analyze model performance through structured experimentation.

---

## 🎯 Problem Statement
With the rapid spread of misinformation online, identifying fake news has become critical. This project aims to:
- Classify news articles as **real or fake**
- Compare multiple ML models
- Analyze model performance and limitations

---

## 🗂 Dataset
- Source: Public fake news dataset (Kaggle / similar)
- Features: News title, text content
- Preprocessing:
  - Text cleaning (stopwords removal, punctuation removal)
  - Tokenization
  - TF-IDF vectorization

---

## ⚙️ Models Used
- Logistic Regression
- Naive Bayes

---

## 🧪 Experiments & Results

| Model                | Accuracy | Precision | Recall |
|---------------------|----------|----------|--------|
| Logistic Regression | 92%      | 91%      | 90%    |
| Naive Bayes         | 88%      | 86%      | 85%    |

---

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- Confusion Matrix

---

## 📉 Error Analysis
- Misclassifications often occur in:
  - Satirical or opinion-based articles
  - Articles with neutral tone but misleading content
- Reason:
  - TF-IDF fails to capture deeper semantic meaning
  - Lack of contextual understanding

---

## 🔬 Key Insights
- Logistic Regression outperformed Naive Bayes due to better handling of feature weights
- Feature engineering significantly impacts performance
- Dataset quality and balance are critical

---

## 🚀 Improvements & Future Work
- Implement deep learning models (LSTM, BERT)
- Use word embeddings (Word2Vec, GloVe)
- Improve dataset diversity
- Perform hyperparameter tuning
- Add real-time news classification system

---

## 🛠 Tech Stack
- Python
- Scikit-learn
- Pandas, NumPy
- NLTK
- Matplotlib / Seaborn

---

## 📸 Sample Output
<img src="Screenshot 2026-04-01 014214.png" width="45%"/> 
<img src="Screenshot 2026-04-01 014208.png" width="45%"/>

## 📊 Results Interpretation

- Linear SVM performs slightly better in terms of classification balance
- Logistic Regression shows higher false positives compared to SVM
- The model struggles more with identifying fake news correctly

This suggests that SVM generalizes better on this dataset.
---

## 💡 Conclusion
This project demonstrates how machine learning can be applied to detect misinformation. It also highlights the importance of experimentation, evaluation, and continuous improvement in building reliable ML systems.

---

## 🔗 Author
Khushi Kushwaha  
GitHub: https://github.com/khushhub

---
