# Textile Defect Detection using Computer Vision and GAN

##  Overview
This project focuses on detecting defects in textile fabrics using computer vision techniques and improving model performance using GAN-based data augmentation.

##  Problem Statement
Manual inspection of textile defects is inefficient and error-prone. Existing machine learning models struggle due to limited defect data. This project aims to automate defect detection and address data imbalance using GAN-generated synthetic images.

##  Methodology
1. Dataset Preparation (AITEX + MVTec)
2. Preprocessing and resizing
3. GAN (DCGAN) training on defect images
4. Synthetic defect image generation
5. Dataset augmentation
6. Defect detection using CV model

##  GAN Architecture
- Model: DCGAN (Deep Convolutional GAN)
- Generator: Produces synthetic defect images from noise
- Discriminator: Distinguishes real vs fake images
- Training: Adversarial learning process

##  Dataset
- AITEX Fabric Dataset
- MVTec Anomaly Detection (Carpet category)

## Current Progress
- Dataset collection and preprocessing ✅
- GAN implementation completed ✅
- Initial synthetic images generated ✅
- Model tuning in progress 🔄

##  Future Work
- Improve GAN output quality
- Train defect detection model
- Evaluate performance (before vs after GAN)

##  Novelty
- Combines GAN-based data augmentation with textile defect detection
- Addresses data imbalance problem in textile datasets
- Improves robustness of defect detection models

##  Tools & Technologies
- Python
- PyTorch
- OpenCV
- Google Colab

##  Conclusion
This project demonstrates how GANs can be effectively used to generate synthetic defect data and improve computer vision models for industrial applications.
