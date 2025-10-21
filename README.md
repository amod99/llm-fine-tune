# Fine-Tuning LLMs for Tabular Data

This repository contains a notebook demonstrating how to fine-tune a Large Language Model (LLM) for a tabular dataset.

## 📊 Dataset
We used a publicly available dataset from a Kaggle competition for this demo. The dataset consists of structured tabular data with numerical features and a binary classification target.

## 🧪 Baseline Model
We first trained a simple Multi-Layer Perceptron (MLP) to establish baseline performance.

## 🔁 LLM Fine-Tuning
We explored two approaches to adapt LLMs for tabular data:
- **Text Prompting**: Formatting tabular rows as natural language prompts.
- **Embedded Input**: Feeding tabular features directly as embeddings into a custom transformer architecture.

## 🎯 Custom Transformer Model
We implemented a feature-wise transformer that treats each column as a token, enabling attention across features. This allows the model to learn complex feature interactions.

## 🔍 Attention Visualization
Using the custom transformer, we visualized attention maps to understand:
- How attention varies across different layers
- How feature interactions differ for positive vs negative class samples

## 📁 Contents
- `tabFineTune.ipynb`: End-to-end demo of preprocessing, training, fine-tuning, and visualization
---

Feel free to explore, modify, and extend the notebook for your own tabular modeling tasks!
