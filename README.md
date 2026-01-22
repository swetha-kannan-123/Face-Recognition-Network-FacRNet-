# Enhanced MAFA-GAN + FacRNet Training Framework

This repository contains an advanced face synthesis and recognition training pipeline that integrates:

- Face detection, landmark extraction, pose estimation, and alignment
- **MAFA-GAN** with **3 Generators + Multi-Discriminator**
- Multi-encoder feature extraction:
  - AC-ResNet50 (CNN)
  - Vision Transformer (ViT)
  - Landmark-based Graph / MLP Encoder
- Fusion-aware identity preservation
- **FacRNet** (Spiking Neural Network + MLP)
- Simple **Aquila-Hawk Optimization (AHO)**-style hyperparameter tuning

---

## 📁 Project Structure

