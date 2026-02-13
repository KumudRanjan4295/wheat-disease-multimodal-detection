# 🌾 Multimodal Early Wheat Disease Detection using Hyperspectral–RGB Fusion

🚀 AI-driven precision agriculture system for early wheat disease detection using multimodal deep learning, explainable AI, and hyperspectral imaging.

---

## 📌 Project Overview

Early detection of wheat diseases is critical for improving crop yield and reducing economic loss. Traditional computer vision approaches rely only on RGB images, which detect diseases only after visible symptoms appear.

This project introduces a **multimodal deep learning framework** that combines:

- RGB spatial information
- Hyperspectral spectral signatures

to enable **early and accurate wheat disease detection**.

---

## 🔬 Research Contribution

✔ Multimodal fusion of RGB + Hyperspectral imaging  
✔ Early disease detection using spectral biochemical signals  
✔ Explainable AI using Grad-CAM  
✔ Spectral band importance analysis  
✔ Baseline vs Fusion model performance comparison  

---

## 🧠 Model Architecture

The system consists of three major components:

### 1️⃣ RGB Feature Extractor
- EfficientNet / ResNet backbone
- Extracts spatial disease patterns

### 2️⃣ Hyperspectral Feature Extractor
- CNN-based spectral encoder
- Processes multi-band spectral cubes

### 3️⃣ Multimodal Fusion Network
- Concatenates spatial and spectral features
- Fully connected classifier for disease prediction

---

## 🛠 Tech Stack

- Python
- PyTorch
- Computer Vision
- Multimodal Deep Learning
- Hyperspectral Image Processing
- Captum (Explainable AI)
- Scikit-learn

---

## 📂 Dataset Used

### RGB Dataset
- Wheat Leaf Disease Dataset  
- Source: Kaggle

### Hyperspectral Dataset
- HyperLeaf2024 Dataset  
- Source: Kaggle

---

## ⚙️ Installation

Clone repository:

```bash
git clone https://github.com/YOUR_USERNAME/wheat-disease-multimodal-detection.git
cd wheat-disease-multimodal-detection
