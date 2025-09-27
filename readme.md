# 🧠 Breast Cancer Detection in Mammograms Using Vision Transformer

This repository presents a full deep learning pipeline for classifying **benign vs malignant breast lesions** in mammograms using:

- ✅ **Vision Transformer (ViT)** for global reasoning
- ✅ **ResNet50** for feature extraction
- ✅ Advanced **image preprocessing** (Wavelet Denoising, CLAHE, Unsharp Masking, Pectoral Removal)
- ✅ **CycleGAN + MixUp + CutMix** for rare class augmentation
- ✅ Attention-based **explainability** using **Attention Rollout** and **Grad-CAM**

---

## 📂 Project Structure
📁 breast-cancer-vit-transformer
├── Mammogram_VIT_Model.ipynb # Colab training + attention
├── Project_Report.pdf # Final project report
├── README.md # This file
├── requirements.txt # Python packages
└── .gitignor