# LSTM Language Model using Simple English Wikipedia

## Overview

This project implements a **text generation model using an LSTM (Long Short-Term Memory) neural network** trained on the **Simple English Wikipedia dataset**.

The goal is to build a neural language model capable of predicting the **next word in a sequence**, allowing the model to generate coherent text.

This experiment demonstrates how recurrent neural networks can be used for language modeling before transformer-based architectures became dominant.

---

## Dataset

Dataset used: **Simple English Wikipedia**

The dataset consists of Wikipedia articles extracted from the XML dump.

Processing steps include:

* Extracting article text
* Cleaning the text
* Preparing sequences for model training
* Converting words into numerical representations

The dataset is reduced in size for faster experimentation.

---

## Project Workflow

The notebook follows these steps:

1. **Load Wikipedia Text**

   * Extract text data from processed corpus

2. **Text Cleaning**

   * Remove unwanted characters
   * Normalize whitespace
   * Prepare training corpus

3. **Tokenization**

   * Convert words into tokens
   * Build vocabulary

4. **Sequence Preparation**

   * Create input-output training pairs
   * Convert sequences into numerical format

5. **Model Architecture**

   * Embedding layer
   * LSTM layer
   * Fully connected output layer

6. **Training**

   * Train model to predict next word
   * Use loss function and optimizer

7. **Text Generation**

   * Generate text from a starting prompt

---

## Technologies Used

* Python
* PyTorch
* NumPy
* Text preprocessing

---

## Key Libraries

* torch
* numpy
* re
* collections

---

## How to Run

Clone the repository:

```
git clone https://github.com/YOUR_USERNAME/lstm-language-model-simplewiki
```

Install dependencies:

```
pip install -r requirements.txt
```

Open the notebook:

```
jupyter notebook LSTM_wiki_text1.ipynb
```

---

## Research Motivation

This project explores **recurrent neural network approaches to language modeling** and compares them with more modern transformer-based methods.

It serves as a foundational experiment for understanding sequence modeling in natural language processing.

---

## Author

Sangeetha KV
PhD Mathematics | Machine Learning | Data Science
