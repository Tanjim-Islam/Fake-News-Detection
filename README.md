# Fake News Detection with FaKnow

## Overview

This project leverages the **FaKnow** library, a unified framework for fake news detection algorithms based on PyTorch. FaKnow, short for **Fake News Knowledge**, provides a comprehensive set of tools and models designed to facilitate the development and evaluation of fake news detection algorithms. It includes various state-of-the-art models and is designed for both content-based and social context-based fake news detection. FaKnow is a relatively new library that aims to streamline the process of building and testing fake news detection systems.

## Dataset

The dataset used in this project consists of labeled news articles split into three sets:

- **Training Set**: 26,938 articles
- **Validation Set**: 8,980 articles
- **Test Set**: 8,980 articles

## Requirements

To run this project, the following libraries are required:

```bash
pip install faknow pandas shap
pip install torch_geometric
pip install torch_scatter
pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
```

## Detailed Accuracy

After training the model with FaKnow, the following accuracy metrics were achieved:

### Training Set
- **Accuracy**: 1.0
- **Precision**: 1.0
- **Recall**: 1.0
- **F1-Score**: 1.0

### Validation Set
- **Accuracy**: 0.9994432330131531
- **Precision**: 1.0
- **Recall**: 0.9988323213451659
- **F1-Score**: 0.9994158196050941

### Test Set
- **Accuracy**: 0.9992204904556274
- **Precision**: 0.9995366079703429
- **Recall**: 0.9988423246121787
- **F1-Score**: 0.999189345686161

The high accuracy metrics across all datasets indicate the effectiveness of the FaKnow framework and the chosen model in detecting fake news. The project demonstrates the potential of using advanced machine learning models for reliable and robust fake news detection.