# Skin Cancer Detection Using Deep Learning Techniques
This repository contains Jupyter notebooks implementing deep learning models for Skin Cancer Detection and Segmentation. The project progresses from simple binary/multi-class classification to advanced segmentation using U-Net variants and hybrid models. It uses datasets like HAM10000 (for 2/7 labels) and DermNet/Skin Disease (for 9 classes).

## Project Overview
- **Goal**: Detect and segment skin lesions (benign vs. malignant, or multi-class diseases) using CNNs, transfer learning, and U-Net architectures.
- **Techniques**: Custom CNNs, Inception-ResNet-V2 transfer learning, U-Net for segmentation, Fuzzy U-Net enhancements.
- **Datasets**:
  - HAM10000 (2/7 labels: ~10k images for binary/multi-class classification).
  - DermNet/Skin Disease (9 classes: e.g., Eczema, Psoriasis, Melanoma; ~3k images for advanced tasks).
- **Key Results** (from notebooks):
  - Simple 2-Label Classification: ~92% accuracy.
  - Simple 7-Label Classification: ~78% accuracy.
  - U-Net Segmentation: IoU ~0.75 on test set.
  - Fuzzy U-Net: Improved IoU ~0.82 with fuzzy loss.
  - Advanced Multi-Class: ~85% top-1 accuracy with Inception-ResNet-V2.
  - Hybrid Model: ~88% accuracy + 0.80 IoU.

  
