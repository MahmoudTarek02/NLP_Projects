# Project 2 — Word Embeddings and Named Entity Recognition

## Overview

This project focuses on learning distributed word representations using the Word2Vec Skip-Gram model with Negative Sampling (SGNS) and applying these embeddings to the Named Entity Recognition (NER) task.

The project explores both neural and probabilistic approaches for sequence labeling and compares their performance on a real-world NER dataset.

## Dataset

- CoNLL-2003 Named Entity Recognition Dataset
- Source: Hugging Face (`lhoestq/conll2003`)

The dataset contains annotated text with entity labels such as:

- Person (PER)
- Organization (ORG)
- Location (LOC)
- Miscellaneous (MISC)

## Part 1: Word2Vec Embedding Learning

### Objectives

Learn dense vector representations of words using the Skip-Gram with Negative Sampling (SGNS) algorithm.

### Implemented Features

- Corpus preprocessing
- Vocabulary construction
- Skip-Gram architecture
- Negative Sampling
- Embedding training
- Loss monitoring
- Embedding persistence and loading

### Word Analogy Task

Implemented semantic analogy reasoning using learned embeddings:

```text
king - man + woman ≈ queen