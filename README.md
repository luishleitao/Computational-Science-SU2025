# Protein Sequence Analysis — Machine Learning Project

This repository contains the implementation and analysis for the project **"Unsupervised and Supervised Analysis of Protein Sequences"**, carried out in the course **Computational Science – Machine Learning for Physicists** at Sorbonne Université, under the supervision of Martin Weigt.

## 📋 Project Overview

The project aims to apply basic machine learning methods (unsupervised and supervised) to protein sequences. It includes:

- Preprocessing and encoding of multiple-sequence alignment (MSA) data
- Dimensionality reduction (PCA)
- Clustering (k-means, hierarchical)
- Binary classification (logistic regression, random forests, neural networks)
- Generative modeling of protein sequences

All tasks are implemented and demonstrated in the provided Jupyter notebook.

## 📁 Files in this Repository

- `Project_Luis_Joan.ipynb`: Main Colab notebook containing the full analysis, visualizations, and code.
- `project.pdf`: Original project description and instructions by the course instructor.
- `README.md`: This documentation file.

## 🧬 Dataset Description

The dataset is provided in FASTA format and includes:

- **Natural sequences** (used for training)
- **Artificial sequences** (generated from a trained generative model)

Each protein sequence entry contains a label indicating if it is **functional** or **non-functional**.

## 🧠 Tasks Implemented

### 1. One-Hot Encoding
- Categorical amino acid symbols are mapped to 20-dimensional one-hot vectors.
- Gaps are encoded as zero-vectors.

### 2. PCA (Principal Component Analysis)
- Dimensionality reduction to visualize sequence distributions.
- Color-coded by functionality.
- Projection of both natural and artificial sequences.

### 3. Clustering
- Analysis of cluster composition and relation to functionality.

### 4. Functionality Classification
- Supervised training of classifiers (e.g., logistic regression).
- Evaluation on both natural and artificial sequences.
- Metrics: TP, TN, FP, FN with discussion of soft classifier thresholds.

### 5. Sequence Generation
- A generative model is trained to sample new sequences.
- Evaluation of generated sequences' plausibility and predicted functionality.


## 📊 Results

Key findings include:
- Clear separation between functional and non-functional sequences in PCA space.
- Clustering partially aligns with functionality.
- Classifiers achieve reasonable accuracy.
- Generated sequences exhibit functional-like properties under the trained model.

## 👥 Authors

- **Luís Leitão**
- **Joan Descoubes**



