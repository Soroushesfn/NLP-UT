# Natural Language Processing (NLP) — Course Implementations

[![University](https://img.shields.io/badge/University-University%20of%20Tehran-blue.svg)](https://ut.ac.ir/en)
[![Topic](https://img.shields.io/badge/Domain-NLP%20%26%20Deep%20Learning-success.svg)](#)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blueviolet.svg)](https://www.python.org/)

This repository contains my personal implementations, code solutions, and practical experiments for the Natural Language Processing (NLP) course at the **University of Tehran**. 

Rather than just theoretical exercises, this repository focuses on hands-on engineering—ranging from fundamental text processing to fine-tuning large language models for Persian language tasks.

---

## 🚀 Implemented Functions & Core Topics

Here are the primary technical implementations explored across the course assignments:

### 1. Text Profiling & Preprocessing
*   **Persian Text Normalization:** Custom pipelines for cleaning, tokenizing, and normalizing Persian text corpora using standard NLP libraries.
*   **Statistical Profiling:** Extracting linguistic features, tracking n-gram frequencies, and mapping dataset distributions.

### 2. Word Representation & Embeddings
*   **Static Embeddings:** Implementation of traditional word vector models to capture baseline semantic relationships.
*   **Contextual Embeddings:** Extracting dynamic, context-aware token representations using Transformer architectures.
*   **Comparative Analysis:** Benchmarking the performance, strengths, and limitations of static versus contextual embeddings on downstream evaluation tasks.

### 3. Model Fine-Tuning & Sentence Equivalence 
*   **Sentence Pair Tasks:** Engineering pipelines to detect semantic similarity and equivalence between text pairs.
*   **ParsBERT Fine-Tuning:** Adapting `HooshvareLab/bert-fa-base-uncased` on parallel datasets (e.g., ParsMap formal-informal pairs) to classify semantic relationships in Persian text.

---

## 🛠 Tech Stack

*   **Languages & Utilities:** Python
*   **Deep Learning:** PyTorch, Hugging Face `transformers`
*   **Data Processing:** Pandas, NumPy
*   **Vectorization & ML:** Scikit-learn

---

## 📂 Repository Structure

```
NLP-UT/
├── Assignment_1_Text_Profiling/
│   ├── preprocessing.py
│   └── statistical_analysis.ipynb
├── Assignment_2_Embeddings/
│   ├── static_vs_contextual.ipynb
│   └── vector_utils.py
├── Assignment_3_ParsBERT_FineTuning/
│   ├── dataset_loader.py
│   ├── train_equivalence.py
│   └── model_evaluation.ipynb
├── requirements.txt
└── README.md
```
