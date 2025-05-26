# 🧠 Brain Tumor Classification with Explainable AI

This project aims to accurately classify brain tumors from MRI scans using deep learning models enhanced with **Explainable AI (XAI)** techniques, ensuring transparency and trust in clinical settings.

---

## 🚀 Problem Statement

Traditional AI systems for brain tumor detection lack transparency, limiting their acceptance in medical practice. This project addresses the issue by combining **deep learning** with **XAI methods like LIME**, helping clinicians understand the decision-making process behind predictions.

---

## 🎯 Objectives

- Build robust CNN and ResNet50 models to classify brain tumors from T1-weighted contrast-enhanced MRI images.
- Integrate **LIME** to provide interpretable heatmaps explaining model predictions.
- Benchmark performance on multiple tumor classes and ensure transparency of AI decisions.

---



## 🧩 Workflow

1. **Dataset Acquisition**: MRI dataset with 4 classes — Glioma, Meningioma, Pituitary, and No Tumor.
2. **Preprocessing**: Image resizing (255x255), cropping, denoising (Gaussian filter), normalization, and data augmentation.
3. **Model Training**: 
   - CNN (10 epochs, batch size 16)
   - ResNet50 (50 epochs, batch size 32)
4. **Prediction & Evaluation**: Accuracy, categorical cross-entropy loss.
5. **Explainability**: 
   - LIME with Quickshift segmentation
   - Heatmaps highlighting influential regions in MRI scans

---

## 📊 Results

<!-- Upload your plots or heatmaps here -->
###  1. Project Workfloww

![Workflow](https://github.com/asanmo2004/Brain_Tumor_Classification_using_XAI/blob/main/Screenshots/WorkFlow.png)

---

###  2. Predicted Classification

![Predicted](https://github.com/asanmo2004/Brain_Tumor_Classification_using_XAI/blob/main/Screenshots/Predicted%20Outputs.png)

---

###  3. Lime Output for CNN

![CNN](https://github.com/asanmo2004/Brain_Tumor_Classification_using_XAI/blob/main/Screenshots/Lime%20Output%20for%20CNN.png)

---

### 📈 4. Lime Output for Resnet50
![Resnet50](https://github.com/asanmo2004/Brain_Tumor_Classification_using_XAI/blob/main/Screenshots/Lime%20Output%20for%20Resnet.png)

---

### 📉 5. Training Accuracy

![Accuracy](https://github.com/asanmo2004/Brain_Tumor_Classification_using_XAI/blob/main/Screenshots/Accuracy.png)

## ⚙️ Tech Stack

- **Language**: Python 3.6+
- **Frameworks**: TensorFlow 2.x, Keras
- **Explainability**: LIME
- **Libraries**: NumPy, Pandas, Matplotlib, OpenCV, Scikit-learn

---

## 🖥️ Hardware Requirements

- CPU: Intel i5 / Ryzen 5 or higher
- RAM: 8 GB minimum (16 GB recommended)
- GPU: NVIDIA GTX 1060 (Recommended: RTX 3060+)
- Storage: SSD (1 TB preferred)

---

## 📦 Dataset

- **Source**: [Kaggle - Brain Tumor MRI Dataset by Masoud Nickparvar](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)

---

## 🧪 Evaluation Metrics

- **Accuracy**
- **Categorical Cross-Entropy Loss**

---
