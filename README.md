# Agentic Fake News Detection System

An advanced Natural Language Processing (NLP) pipeline that combines a fine-tuned **DistilBERT** classification model with an intelligent **three-agent architecture** to detect and explain misleading online content. 

## 🚀 Project Overview
Instead of treating machine learning models as an unexplainable "black box," this system implements an agentic layer over a Deep Learning backbone. Every prediction is backed by structural text evaluation and a human-readable, plain-English explanation.

### Key Features
- **Core Classifier:** DistilBERT (`distilbert-base-uncased`) fine-tuned on a balanced dataset of ~20,000 news articles, achieving an **accuracy of ~96%** and an F1-score above 0.95.
- **Agentic Layer:** 1. **Analysis Agent:** Parses semantic flags, linguistic patterns, and simple heuristics.
  2. **Verification Agent:** Cross-examines internal features and resolves conflicts when model confidence signals are mixed.
  3. **Decision Agent:** Aggregates findings and translates deep-learning probabilities into concrete, explainable human text.

## 🛠️ Tech Stack
- **Languages:** Python
- **Libraries:** Hugging Face Transformers, PyTorch, Scikit-Learn, Pandas, NumPy
- **Models:** DistilBERT
- **Environment:** Jupyter Notebook / Google Colab (T4 GPU accelerated)

## 📊 Dataset Era & Limitations
The backbone model was optimized using historical datasets (2016–2017). Future iterations aim to integrate real-time web search verification APIs to catch modern, evolving misinformation patterns.