#  AgrBot: Agricultural Question Answering Bot

AgriBot is a domain-specific chatbot designed to answer questions related to agriculture. It leverages transformer-based language models to provide accurate and relevant responses using a fine-tuned QA model trained on an agriculture-focused dataset.

---

##  Project Overview

This project demonstrates the development and evaluation of a question-answering chatbot using a Hugging Face Transformer model, fine-tuned on a custom agricultural dataset. The goal is to support farmers and agriculture professionals by offering automated, intelligent answers to domain-specific questions.

---

##  Contents

- `AgriBot.ipynb`: Jupyter Notebook containing code for:
  - Data loading and preprocessing
  - Model fine-tuning and evaluation
  - Inference and sample responses
- `agriculture_dataset`: Domain-specific QA dataset

---

##  Features

- Utilizes Hugging Face's `Transformers` library
- Fine-tunes a transformer model like `DistilBERT`
- Supports interactive question-answering
- Tracks performance with key evaluation metrics

---

##  Requirements

To run this notebook, install the following packages:

```bash
pip install transformers datasets torch scikit-learn
```
## Demo video
- Dataset Link: https://huggingface.co/datasets/KisanVaani/agriculture-qa-english-only
- Demo video Link: https://www.youtube.com/watch?v=S39_UNUPVQs

