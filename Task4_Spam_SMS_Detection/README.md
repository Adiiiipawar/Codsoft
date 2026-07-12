# 📱 Task 4 — Spam SMS Detection
## CodSoft ML Internship | Batch C6 | Aditya Pawar

![Python](https://img.shields.io/badge/Python-3.x-blue)
![ML](https://img.shields.io/badge/ML-NLP-green)
![Gradio](https://img.shields.io/badge/UI-Gradio-orange)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 🚀 Live Demo
👉 [Try the Spam SMS Detector here](https://c4c3f072069ec6c9c1.gradio.live)

---

## 📌 Objective
Build an ML model to classify SMS messages as **Spam** or **Ham (Legitimate)**
using NLP techniques and multiple classifiers.

---

## ⭐ What Makes This Different
- 🔴 **WordCloud visualization** — see exactly which words define spam vs ham
- 🤖 **3 models compared** — Naive Bayes vs Logistic Regression vs SVM
- 🛡️ **Two-layer detection** — ML model + keyword rules for modern phishing
- 🌐 **Live Gradio UI** — interactive demo with real-world test cases
- 📊 **Model limitations analysis** — honest reflection on where ML fails

---

## 📊 Results

| Model | Accuracy |
|-------|----------|
| Naive Bayes | ~97% |
| Logistic Regression | ~98% |
| SVM (LinearSVC) | ~98% |

---

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** scikit-learn, pandas, numpy, NLTK, WordCloud
- **Vectorization:** TF-IDF (bigrams)
- **UI:** Gradio
- **Environment:** Google Colab

---

## 📁 Files
- `spam_sms_detection.ipynb` — Main notebook
- `spam.csv` — Dataset (UCI SMS Spam Collection)

---

## 🔍 Key Findings
- Spam messages are significantly longer than ham on average
- Words like "free", "win", "claim", "urgent" are strong spam indicators
- Modern phishing scams (bank alerts, delivery scams) bypass traditional models
- Two-layer detection (ML + keywords) handles both traditional and modern spam

---

## 📎 Dataset
[UCI SMS Spam Collection — Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

---

*Built with ❤️ by Aditya Pawar | CodSoft ML Internship C6*
