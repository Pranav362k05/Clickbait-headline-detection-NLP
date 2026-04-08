# 📰 Clickbait Headline Detection (NLP)

A Machine Learning project to classify news headlines as **Clickbait** or **Non-Clickbait** using NLP techniques.

---

## 📌 Project Overview

This project performs **binary text classification** on news headlines to detect whether they are misleading clickbait or genuine.

---

## 📂 Dataset

- Source: [Clickbait Dataset on Kaggle](https://www.kaggle.com/datasets/amananandrai/clickbait-dataset/data)
- Contains labeled headlines:
  - `1` → Clickbait  
  - `0` → Non-clickbait  

---

## ⚙️ Tech Stack

- Python 🐍
- Google Colab
- Pandas
- Scikit-learn

---

## 🧠 Methodology

### 🔹 1. Data Collection
- Dataset downloaded using Kaggle API

### 🔹 2. Preprocessing
- Lowercasing text
- Removing punctuation & noise

### 🔹 3. Feature Extraction
- **TF-IDF Vectorization**
  - Converts text into numerical vectors

### 🔹 4. Model Training
- Logistic Regression ✅ (Primary)
- Naive Bayes (Comparison)

### 🔹 5. Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 📊 Results
Accuracy: 0.97

Precision: 0.96
Recall: 0.97
F1-score: 0.96


> ⚡ Logistic Regression performed best due to its efficiency with high-dimensional sparse text data.

---

## 📈 Why Logistic Regression?

- Works well for **linear text classification problems**
- Handles **high-dimensional TF-IDF features**
- Fast and interpretable
- Outputs probability scores

---

## 📌 Project Pipeline

1. Load dataset  
2. Preprocess text  
3. Convert text → TF-IDF vectors  
4. Train model  
5. Evaluate performance  

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/Pranav362k05/Clickbait-headline-detection-NLP
```
2. Open in Google Colab / Jupyter Notebook
3. Run all cells

## 📎 Files

Clickbait_Detection.ipynb → Main notebook
README.md → Project documentation
