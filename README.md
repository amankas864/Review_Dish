
# 🧠 NLP-Powered Customer Review Analysis System

A complete Natural Language Processing (NLP) pipeline to analyze large-scale customer reviews and social media comments. This capstone project extracts insights, classifies sentiment, identifies key topics and trends, and recommends business strategies through a rich set of visualizations and machine learning models.

---

## 📌 Table of Contents

- [Overview](#overview)
- [Objectives](#objectives)
- [Tech Stack](#tech-stack)
- [Project Pipeline](#project-pipeline)
- [Installation](#installation)
- [Dataset](#dataset)
- [Screenshots](#screenshots)
- [Results](#results)
- [Future Work](#future-work)
- [Contributors](#contributors)

---

## 📖 Overview

This project leverages NLP techniques and machine learning models to analyze text reviews from customers. It transforms unstructured review data into actionable business insights through sentiment classification, topic modeling, trend analysis, and interactive dashboards.

---

## 🎯 Objectives

- Understand **customer sentiment** across reviews
- Identify **frequently mentioned topics and keywords**
- Classify reviews by **sentiment and intent**
- Recommend data-driven **business improvements**
- Provide **visual reports** through interactive dashboards

---

## 🧰 Tech Stack

| Component          | Tool/Library                   |
|-------------------|--------------------------------|
| Language           | Python                         |
| Notebook           | Google Colab / Jupyter         |
| NLP Libraries      | NLTK, spaCy, TextBlob, BERTopic|
| Vectorization      | TF-IDF, Word2Vec, BERT         |
| ML Models          | Logistic Regression, SVM, Naive Bayes, LSTM |
| Topic Modeling     | LDA, BERTopic                  |
| Trend Analysis     | Pandas, Matplotlib, Seaborn    |
| Dashboards         | Streamlit, Plotly              |
| NER                | spaCy                          |
| Reporting          | PDF (LaTeX/Markdown Export)    |

---

## 📈 Project Pipeline

### ✅ 1. Data Preprocessing

- Removed noise (HTML, symbols)
- Lowercased, tokenized, and lemmatized
- Vectorized using TF-IDF, Word2Vec, and BERT

### ✅ 2. Exploratory Text Analysis

- Word clouds by sentiment class  
- N-gram frequency analysis  
- Ratings by product & time period

### ✅ 3. Sentiment Classification

- Trained models: Logistic Regression, Naive Bayes, SVM  
- Evaluated with Confusion Matrix, Precision, Recall, AUC

### ✅ 4. Topic Modeling

- LDA and BERTopic to extract major discussion points  
- Topics mapped to high/low ratings  

### ✅ 5. Trend Analysis

- Time-series plots of sentiment over months/years  
- Spike detection after product launches

### ✅ 6. Named Entity Recognition (NER)

- Used spaCy to extract entities: brands, places, product names

### ✅ 7. Insight Generation

- Identified common praise/complaints  
- Suggested strategic improvements

### ✅ 8. Reporting & Visualization

- Built interactive dashboard using Streamlit + Plotly  
- Exported final PDF/Word report with summaries and charts

---

## 📂 Dataset

We used publicly available customer review datasets with:

- `text` – full customer review  
- `score` – star rating (1–5)  
- `time` – UNIX timestamp  
- `productId`, `userId`, etc. (optional)

📥 **Dataset Link**: [Amazon Reviews (Kaggle)](https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products)

💡 Used 10,000–50,000 samples for optimal performance.

---

## 📸 Screenshots

> 📌 Paste your visuals here

### 🔹 Word Clouds

![wordcloud-positive](screenshots/wordcloud_positive.png)

### 🔹 Model Performance

![confusion-matrix](screenshots/confusion_matrix.png)

### 🔹 Sentiment Over Time

![sentiment-trend](screenshots/sentiment_trend.png)

### 🔹 BERTopic Clusters

![bertopic-viz](screenshots/bertopic_visualization.png)

---

## 🧪 Results Summary

| Model             | Accuracy | Precision | Recall | F1-Score |
|------------------|----------|-----------|--------|----------|
| Logistic Regression | 0.88     | 0.89      | 0.86   | 0.87     |
| SVM              | 0.86     | 0.87      | 0.85   | 0.86     |
| Naive Bayes      | 0.82     | 0.84      | 0.80   | 0.82     |

- Top topics: "delivery delay", "great sound", "battery life", etc.
- Sentiment spikes aligned with sales events & product launches

---

## 🔭 Future Work

- Use multilingual datasets
- Integrate audio/video sentiment (AssemblyAI)
- Real-time dashboard updates
- Deploy full app with feedback API

---

## 👥 Contributors

- Aman Kashyap – Developer, Analyst, Report Designer

---

## 📄 License

MIT License. Attribution appreciated.

---

## 📝 Report

📄 Final report PDF: [`Customer_Review_Analysis_Report.pdf`](final-report.pdf)

📁 Includes:
- Executive summary
- Sentiment insights
- Classifier results
- Actionable recommendations

---
