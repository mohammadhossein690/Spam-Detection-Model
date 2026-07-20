# 📧 Intelligent Spam Detection using NLP

This project implements a text classification model to automatically detect and filter spam messages using the **Naive Bayes** algorithm.

## Key Highlights

* **Technique:** Natural Language Processing (NLP) with text preprocessing and vectorization.
* **Model:** Naive Bayes Classifier.
* **Goal:** Improve communication security by accurately classifying spam and legitimate (ham) messages.

## Methodology

* **Preprocessing:** Cleaning text data (lowercasing, tokenization, removing stopwords, and text normalization).
* **Feature Extraction:** Converting text into numerical representations using **CountVectorizer**.
* **Modeling:** Training a **Naive Bayes** classifier for binary text classification (**Spam vs. Ham**).
* **Validation:** Evaluating model robustness using **10-Fold Cross Validation**.

## 📈 Key Results

* **Model:** Naive Bayes
* **Test Accuracy:** **97.99%**
* **10-Fold Cross Validation Accuracy:** **97.87% ± 0.82%**
* **Confusion Matrix:**

  ```
  [[1191   16]
   [  12  174]]
  ```
* **Classification Report:**

| Class    | Precision | Recall | F1-Score |
| -------- | --------: | -----: | -------: |
| Ham (0)  |      0.99 |   0.99 |     0.99 |
| Spam (1) |      0.92 |   0.94 |     0.93 |

* **Overall Accuracy:** **97.99%**
## 🛠 Tech Stack

Python • Pandas • NumPy • Scikit-learn • NLTK

## ▶️ How to Run

Install dependencies:

```bash
pip install -r requirements.txt
```
