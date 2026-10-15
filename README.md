# OIBSIP-Autocomplete-Autocorrect-NLP
# 🔤 Autocomplete & Autocorrect NLP Dashboard

> An NLP-based Autocomplete and Autocorrect system using **Bigram**, **Trigram**, and **Levenshtein Edit Distance**, featuring an interactive **Streamlit** dashboard.

**Oasis Infobyte | Data Analytics Internship | Level 2 – Task 5**

---

## 📌 Overview

An interactive NLP application built on the **WikiText-2** dataset that predicts the next word and corrects spelling errors in real time.

## ✨ Features

- **Bigram and Trigram Autocomplete** – predicts the next word from the preceding context
- **Levenshtein Edit-Distance Autocorrect** – suggests the closest valid word for misspelled input
- **Model Evaluation** – Precision, Recall, and Accuracy metrics
- **Interactive Streamlit Dashboard** – type text and get live suggestions
- **Word-Frequency Analysis and Model Comparison** – visualize the corpus and compare model performance

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python |
| Data Handling | Pandas |
| NLP | NLTK |
| Machine Learning | Scikit-learn |
| Visualization | Plotly |
| Web App | Streamlit |

## 📂 Dataset

**WikiText-2** – a language-modeling corpus extracted from verified Good and Featured Wikipedia articles.

## 🧠 How It Works

1. **Preprocessing** – tokenize and clean the WikiText-2 corpus
2. **N-gram Models** – build bigram and trigram frequency tables for next-word prediction
3. **Autocorrect** – compute Levenshtein edit distance against the vocabulary and rank candidates by distance and frequency
4. **Evaluation** – measure Precision, Recall, and Accuracy on held-out data
5. **Dashboard** – serve everything through an interactive Streamlit interface

## 📊 Dashboard Highlights

- Live next-word suggestions
- Spelling correction suggestions
- Word-frequency charts
- Bigram vs. Trigram model comparison

## 🎓 Internship Details

- **Organization:** Oasis Infobyte
- **Program:** Data Analytics Internship
- **Level:** 2
- **Task:** 5 – Autocomplete & Autocorrect

