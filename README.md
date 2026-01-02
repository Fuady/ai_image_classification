# AI-Image Classification: Real vs AI-Generated Images  

## Project Overview

This project focuses on building and evaluating machine learning and deep learning models to classify images as **real** or **AI-generated (synthetic)**. We use the *CIFAKE: Real and AI-Generated Synthetic Images* dataset from Kaggle as the benchmark dataset for this task.

---

## Dataset Description

**Dataset Name:** CIFAKE: Real and AI-Generated Synthetic Images  
**Source:** Kaggle (https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images)  
**Task Type:** Binary Image Classification (Real vs Fake)

**Dataset Highlights:**

- **Total Images:** ~120,000  
  - 60,000 *Real* images from the CIFAR-10 dataset
  - 60,000 *AI-Generated* images created using Stable Diffusion v1.4 
- **Image Size:** 32×32 (RGB)  
- **Split:**  
  - Training: 100,000 images (50,000 per class)  
  - Testing: 20,000 images (10,000 per class)

The dataset is balanced across *Real* and *Fake* classes, enabling unbiased training and evaluation.

---

## Project Goals

1. **Understand the dataset** and perform exploratory data analysis.  
2. **Preprocess the images** for model compatibility (normalization, resizing, augmentations).  
3. **Train and evaluate multiple models** including:
   - Traditional Machine Learning (e.g., SVM)  
   - Convolutional Neural Networks (CNNs)  
   - Transfer Learning Models (e.g., ResNet, VGG)  
4. Compare performance using standard metrics:
   - Accuracy  
   - Precision  
   - Recall  
   - F1-Score  
   - ROC-AUC  

---