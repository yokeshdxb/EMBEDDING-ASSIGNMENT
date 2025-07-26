# Embedding Assignment
# Text Embedding Techniques Exploration

This repository contains a comprehensive implementation of various text embedding techniques applied on the IMDb movie reviews dataset. The goal is to understand and compare how different embedding methods convert raw text into meaningful numerical representations for natural language processing (NLP) tasks.

## Project Overview

Text embeddings are crucial for transforming unstructured text data into structured numerical vectors that machine learning models can interpret. This project explores:

- **Classical Embeddings:** Bag of Words (BoW), TF-IDF  
- **Pretrained Word Embeddings:** Word2Vec, GloVe, FastText  
- **Contextual Embeddings:** BERT (Bidirectional Encoder Representations from Transformers)

Each method offers different advantages and trade-offs in terms of dimensionality, semantic understanding, and computational complexity.

## Dataset

- **IMDb Movie Reviews** dataset from Hugging Face Datasets library  
- Subset of 1000 samples for demonstration and faster processing

## Repository Contents

- `embedding_assignment.ipynb`: Jupyter/Colab notebook implementing data preprocessing and all embedding techniques step-by-step  
- `requirements.txt`: Python dependencies required to run the notebook  
- `glove.6B.100d.txt`: Pretrained GloVe embeddings (100-dimensional vectors) downloaded from [Stanford NLP](https://nlp.stanford.edu/projects/glove/)

## Installation

Recommended to run in a fresh [Google Colab](https://colab.research.google.com) environment.

Alternatively, set up a local Python environment:

```bash
pip install -r requirements.txt

