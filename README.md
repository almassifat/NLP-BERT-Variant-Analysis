# NLP-BERT-Variant-Analysis
Comparative Analysis of BERT Variants for Sentiment Classification
# 🚀 BERT Variants Sentiment Analysis on IMDb Dataset

![Python](https://img.shields.io/badge/Python-3.9-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-red)
![Transformers](https://img.shields.io/badge/Transformers-🤗-yellow)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Overview

This project presents a **comparative analysis of five BERT-based transformer models**—**BERT**, **RoBERTa**, **DistilBERT**, **ALBERT**, and **XLNet**—for **binary sentiment classification** on the IMDb movie reviews dataset.  
We evaluate each model’s **performance, efficiency, and robustness**, providing a comprehensive understanding of their strengths and weaknesses.

---

## ✨ Features

✅ Fine-tuned **five BERT variants** on IMDb dataset  
✅ Detailed **performance metrics**: Accuracy, F1-Score, MCC, AUC-ROC, etc.  
✅ **Training curves** (loss & accuracy) for each model  
✅ Comparative **result tables and analysis**  
✅ Identifies **best model (RoBERTa)** with architectural reasoning  
✅ Clean and modular codebase for easy experimentation  

---

## 🧠 Models Evaluated

- **BERT** – Baseline transformer model  
- **RoBERTa** – Robustly optimized BERT  
- **DistilBERT** – Lightweight distilled version  
- **ALBERT** – Parameter-efficient BERT  
- **XLNet** – Permutation-based language model  

---

## 📊 Results Summary

| Model       | Accuracy | F1-Score | AUC-ROC |
|-------------|----------|----------|---------|
| BERT         | 86.4%    | 86.9%    | 0.938   |
| **RoBERTa**  | **89.5%**| **89.9%**| **0.961**|
| DistilBERT   | 86.1%    | 85.9%    | 0.940   |
| ALBERT       | 86.7%    | 86.8%    | 0.941   |
| XLNet        | 89.5%    | 89.6%    | 0.961   |

📌 **RoBERTa** emerged as the **top-performing model**, achieving the highest accuracy, F1-score, and AUC-ROC.

---

## 🖼️ Training Curves

![Training Curves](docs/training_curves.png)

---

## ⚙️ Installation

```bash
git clone https://github.com/yourusername/bert-variants-sentiment.git
cd bert-variants-sentiment
pip install -r requirements.txt
