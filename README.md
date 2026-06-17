# NLP_Basic (by Prof. Kim 2026.05)

Welcome to the **NLP_Basic** repository. This project provides foundational and advanced Jupyter Notebook tutorials for Natural Language Processing (NLP), focusing on text tokenization and sentiment analysis. It was originally curated by **Prof. Kim (May 2026)** and is designed to run seamlessly in Google Colab or local Jupyter environments.

## Overview
This repository offers practical implementations of both English and Korean NLP tasks. It covers essential text preprocessing techniques using NLTK and KoNLPy, and progresses to advanced sentiment analysis and emotion classification using the KoBERT transformer model.

## Repository Contents

### 1. Tokenization and Morphological Analysis
- **`NLTK_Tokenization_Eng.ipynb`:** A comprehensive guide to English text tokenization and preprocessing utilizing the NLTK (Natural Language Toolkit) library.
- **`KoNLPy_형태소분석_ipynb의_사본.ipynb`:** Korean morphological analysis demonstrating how to parse and process Korean text using the KoNLPy library.

### 2. KoBERT-based Emotion and Sentiment Analysis
- **`NLPEmotion_KoBERT_colab.ipynb`:** A tutorial on performing emotion classification on Korean text using the pre-trained KoBERT model.
- **`kobert_sentiment_finetunning_colab.ipynb`:** A step-by-step notebook for fine-tuning the KoBERT model for sentiment analysis tasks.
- **`kobert_sentiment_finetunning_colab_fixed.ipynb` / `..._updated.ipynb`:** Updated and patched versions of the fine-tuning notebook containing bug fixes and performance improvements.

## Prerequisites & Environment
Since the project consists entirely of Jupyter Notebooks (100%), it is highly recommended to use **Google Colab** to easily access GPU acceleration for the KoBERT fine-tuning tasks. 
If running locally, you will need to configure your environment with the following dependencies: Python 3.x, Jupyter Notebook, NLTK, KoNLPy, PyTorch, and the Hugging Face `transformers` library.

## Getting Started
To get started, simply clone the repository and open the notebooks in your preferred environment:
```bash
git clone https://github.com/hopeof-Greatmind/NLP_Basic.git
cd NLP_Basic

