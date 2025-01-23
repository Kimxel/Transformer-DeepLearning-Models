# Transformer-DeepLearning-Models
This repository contains Jupyter notebooks for training and evaluating Vision Transformer (ViT) and Data-Efficient Image Transformer (DeiT) models with applications for prostate cancer metastasis detection using MRI images. The repository focuses on model implementation, evaluation metrics (ROC and CM), and visualization.

## Features
- **Models**:
  - Vision Transformer (`vit_b_16`)
  - Data-Efficient Image Transformer (`deit_base_distilled_patch16_224`)
- **Multi-Class Classification**:
  - Supports metastasis stages: M0, M1a, M1b, and M1c.
- **Performance Metrics**:
  - Confusion matrices for validation and test datasets.
  - ROC curves and AUC scores for multi-class evaluation.

## Requirements
- Python 3.8+
- Jupyter Notebook
- PyTorch 1.13+
- torchvision 0.14+
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- tqdm

Install dependencies with:
```bash
pip install -r requirements.txt
