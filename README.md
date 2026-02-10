# Deep-Learning-for-Pattern-Recognition-Multi-Class-Classification (PyTorch)
## Overview

This project implements an end-to-end deep learning pipeline for multi-class medical image classification using PyTorch. The goal is to design, train, and evaluate convolutional neural networks (CNNs) for skin lesion image classification while addressing real-world challenges such as class imbalance, data quality, and model generalisation.

The project follows a production-style workflow, from dataset exploration and preprocessing to model experimentation and performance tracking.

---

## Objectives

- Build a baseline CNN for medical image classification

- Design a custom PyTorch Dataset and training loop

- Handle class imbalance using sampling and augmentation techniques

- Improve model performance through architectural and training refinements

- Track and compare experiments using Weights & Biases

---

## Dataset & Problem Context

The dataset consists of labelled skin lesion images across multiple diagnostic classes. Key challenges addressed in this project include:

- Imbalanced class distribution

- Visual similarity between lesion categories

- Limited sample sizes for certain classes

---

## Technical Stack

- Python

- PyTorch

- torchvision

- PIL

- pandas

- NumPy

- Weights & Biases (wandb)

---
## Key Concepts Demonstrated

- Custom Dataset and DataLoader implementation in PyTorch

- CNN architecture design and experimentation

- Training and validation loop construction

- Data augmentation for improved generalisation

- Handling imbalanced datasets

- Experiment tracking and metric comparison

- Model evaluation using accuracy and UAR (Unweighted Average Recall)

---
## Project Structure
```css
├── medical_image_classification_pytorch.ipynb
├── README.md
└── requirements.txt
```
---
##Model Development Workflow

1. Exploratory Data Analysis

  - Image inspection

  - Class distribution analysis

2. Baseline Model

  - Custom CNN architecture

  - Initial training and evaluation

3. Data Improvements

  - Class imbalance handling

  - Data augmentation strategies

4. Model Optimisation

  - Architectural refinements

  - Regularisation techniques

5. Training strategy tuning

  - Experiment Tracking

  - Metrics and loss tracking with Weights & Biases

  - Comparative analysis across runs
---


