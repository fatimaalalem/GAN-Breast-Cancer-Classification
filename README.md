# Exploring GAN Variants for Balancing Imbalanced Datasets

## Project Overview
This project compares Vanilla GAN and Wasserstein GAN (WGAN) for handling class imbalance in the Breast Cancer Wisconsin dataset.

The goal is to generate synthetic malignant tumor samples to balance the dataset and improve classification performance.

---

## Dataset
- Breast Cancer Wisconsin Dataset
- 569 total samples
- 30 numerical features
- Classes:
  - Benign (357)
  - Malignant (212)

---

## Project Steps
1. Data preprocessing
2. Feature scaling
3. Training Vanilla GAN
4. Training WGAN
5. Synthetic data generation
6. Dataset balancing
7. Classification using MLPClassifier
8. Performance evaluation

---

## Models Used
- Vanilla GAN
- Wasserstein GAN (WGAN)
- MLPClassifier

---

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Results Summary
- GAN-based balancing improved classification performance.
- Vanilla GAN achieved high Precision.
- WGAN achieved the highest Recall and more stable training.

---

## Repository Contents
- Jupyter Notebook
- Report PDF
- Presentation Slides
- Visualizations
