# Skin Cancer Detection Using Deep Learning Techniques
This repository contains Jupyter notebooks implementing deep learning models for Skin Cancer Detection and Segmentation. The project progresses from simple binary/multi-class classification to advanced segmentation using U-Net variants and hybrid models. It uses datasets like HAM10000 (for 2/7 labels) and DermNet/Skin Disease (for 9 classes).


## Project Overview
- **Goal**: Detect and segment skin lesions (benign vs. malignant, or multi-class diseases) using CNNs, transfer learning, and U-Net architectures.
- **Techniques**: Custom CNNs, Inception-ResNet-V2 transfer learning, U-Net for segmentation, Fuzzy U-Net enhancements.
- **Datasets**:
  - [Skin Cancer MNIST: HAM10000](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000) (2/7 labels: ~10k images for binary/multi-class classification).
  - [Skin cancer: HAM10000](https://www.kaggle.com/datasets/surajghuwalewala/ham1000-segmentation-and-classification/data) (~20k images and masks for binary segmentation)
  - [Dermnet and Skin disease (9 classes)](https://www.kaggle.com/datasets/amrragababdelaziz/dermnet-and-skin-disease-9-classes) (9 classes: e.g., Eczema, Psoriasis, Melanoma; ~3k images for advanced tasks).
- **Key Results** (from notebooks):
  - Simple 2-Label Classification: ~92% accuracy.
  - Simple 7-Label Classification: ~88% accuracy.
  - U-Net Segmentation: IoU ~0.85 on test set.
  - Fuzzy U-Net: Improved IoU ~0.88 with fuzzy loss.
  - Advanced Multi-Class: ~85% top-1 accuracy with Inception-ResNet-V2.
  - Hybrid Model: ~88% accuracy + 0.80 IoU.

  
## Kaggle Notebook Links
- [Simple 2-Label v1](https://www.kaggle.com/code/iakhtar0/skin-cancer-detection-2-labels)
- [Simple 2-Label v2](https://www.kaggle.com/code/iakhtar0/skin-cancer-2-labels-2)
- [Simple 7-Label v1](https://www.kaggle.com/code/iakhtar0/skin-cancer-detection-7-labels)
- [Simple 7-Label v2](https://www.kaggle.com/code/iakhtar0/skin-cancer-7-labels-2)
- [U-Net Segmentation](https://www.kaggle.com/code/iakhtar0/1-skin-cancer-images-segmentation-unet)
- [Fuzzy U-Net Segmentation](https://www.kaggle.com/code/iakhtar0/2-skin-cancer-images-segmentation-fuzzy-unet)
- Advanced ones: Not on Kaggle
