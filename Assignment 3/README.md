# Project 3 — Neural Machine Translation

## Overview

This project implements two Neural Machine Translation (NMT) systems for translating French sentences into English. The goal is to compare a modern Transformer architecture with a recurrent sequence-to-sequence model based on BiLSTMs and additive attention.

Both models were implemented from scratch using PyTorch, with custom attention mechanisms, beam search decoding, evaluation, and visualization components.

---

## Dataset

The project uses a parallel French-English translation dataset provided with the course resources.

### Tokenization

* Byte Pair Encoding (BPE)
* Separate French and English tokenizers
* Training, validation, and test splits

---

## Model 1: Transformer-Based Neural Machine Translation

### Architecture

Encoder-Decoder Transformer with:

* Learned Positional Embeddings
* Multi-Head Self-Attention
* Cross-Attention
* Feed-Forward Networks
* Residual Connections
* Layer Normalization
* Weight Tying between Decoder Embeddings and Output Projection

### Implemented Components

* Custom embedding layer
* Vectorized multi-head attention
* Attention masking
* Positional embeddings
* Encoder stack
* Decoder stack
* Beam search decoding
* Model checkpointing

### Evaluation

* BLEU Score
* Translation examples
* Attention visualization

---

## Model 2: BiLSTM Seq2Seq with Additive Attention

### Architecture

Encoder:

* Bidirectional LSTM

Decoder:

* Unidirectional LSTM

Attention:

* Bahdanau (Additive) Attention

### Implemented Components

* Bidirectional encoder
* Attention score computation
* Context vector generation
* Decoder initialization
* Beam search inference
* Checkpoint saving/loading

### Evaluation

* BLEU Score
* Translation examples
* Attention visualization

---

## Comparison

The project compares two major Neural Machine Translation paradigms:

| Model               | Architecture             |
| ------------------- | ------------------------ |
| Transformer         | Attention-Based          |
| Seq2Seq + Attention | Recurrent Neural Network |

The comparison focuses on:

* Translation quality
* BLEU score
* Training behavior
* Attention patterns
* Inference performance

---

## Technologies

* Python
* PyTorch
* NumPy
* Hugging Face Transformers (Tokenization)
* Matplotlib
* Jupyter Notebook

---

## Key Concepts

* Neural Machine Translation
* Sequence-to-Sequence Learning
* Multi-Head Attention
* Transformer Architecture
* Attention Mechanisms
* Beam Search
* BLEU Evaluation
* Recurrent Neural Networks
* Bidirectional LSTMs

---

## Results

Both models successfully translate French sentences into English and demonstrate the evolution of machine translation from recurrent architectures to attention-based Transformer models.
