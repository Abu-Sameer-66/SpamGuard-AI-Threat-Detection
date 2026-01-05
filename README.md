# 🛡️ SpamGuard  
## AI-Powered SMS Phishing & Spam Detection System

> **SpamGuard** is a production-ready, high-precision **Natural Language Processing (NLP) security engine** designed to detect and neutralize **SMS phishing (smishing) and spam attacks in real time**.  
>  
> Built with **probabilistic machine learning** and **statistical text modeling**, SpamGuard achieves **98%+ classification accuracy** while prioritizing **zero false positives**, ensuring user trust and message integrity.

[![Status](https://img.shields.io/badge/Status-Production%20Ready-success)]()
[![License](https://img.shields.io/badge/License-MIT-blue)]()
[![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB)]()
[![ML](https://img.shields.io/badge/Machine%20Learning-NLP-orange)]()

---

## 🚨 Problem Statement: The SMS Threat Landscape

SMS-based fraud and phishing attacks cost the global economy **billions of dollars annually**.  
Conventional rule-based or keyword-matching filters fail against:

- Linguistic obfuscation  
- Context-aware phishing attempts  
- Evolving attacker vocabulary  

**SpamGuard addresses this gap** by learning the *semantic intent* of messages rather than relying on static keyword lists.

---

## 🧠 Solution Overview

SpamGuard leverages **classical NLP + probabilistic ML** to deliver:

- ⚡ **Real-time detection**
- 🎯 **High-precision filtering (Zero false positives)**
- 🔐 **Security-first design**
- 📈 **Scalable and deployable architecture**

Suitable for:
- Telecom platforms  
- SMS gateways  
- FinTech & Banking alert systems  
- Cybersecurity research pipelines  

---

## ⚙️ System Architecture

SpamGuard follows a **modular, multi-stage NLP pipeline**:

### 1️⃣ Text Preprocessing
- Noise removal (punctuation, symbols)
- Tokenization
- Stopword elimination  
*(NLTK-based pipeline)*

### 2️⃣ Feature Engineering
- **TF-IDF Vectorization**
- Context-weighted term importance
- Sparse high-dimensional text representation

### 3️⃣ Probabilistic Classification
- **Multinomial Naive Bayes**
- Optimized for speed, interpretability, and text-based probability modeling

---

## 📄 Technical Documentation

A detailed explanation of:
- Model design
- Feature selection
- Evaluation methodology
- Future improvements  

📘 **[View Technical Architecture Report (PDF)](./SpamGuard_Technical_Architecture.pdf)**

---

## 🛠️ Technology Stack

| Layer | Technology | Purpose |
|------|-----------|--------|
| Language | Python | Core system implementation |
| NLP | NLTK, Scikit-Learn | Text preprocessing & modeling |
| ML Model | Multinomial Naive Bayes | Probabilistic classification |
| Data Handling | Pandas | Dataset processing |
| Evaluation | Matplotlib | Confusion matrix & metrics |

---

## 📊 Model Performance

| Metric | Value | Interpretation |
|------|-------|---------------|
| Accuracy | **98.4%** | Overall classification reliability |
| Precision | **100%** | Zero false positives (No legitimate SMS blocked) |
| Recall | **94%** | High phishing capture rate |

> **Design Decision:**  
> Precision is deliberately prioritized over recall to preserve **user trust**, a critical requirement in real-world SMS filtering systems.

---

## 🚀 Installation & Usage

### Clone the Repository
```bash
git clone https://github.com/Abu-Sameer-66/SpamGuard-AI-Threat-Detection.git
cd SpamGuard-AI-Threat-Detection
