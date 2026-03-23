# 🧠 Synthetic COVID-19 Chest X-ray Generation (ACGAN)

This project explores the use of generative models to create synthetic COVID-19 chest X-ray images and evaluate their realism and diagnostic consistency.

## 📖 Overview

Medical imaging datasets are often limited due to privacy and annotation costs. This project uses generative models to synthesize realistic chest X-ray images, aiming to improve data availability for training deep learning models.

The main focus is on:

- Generating synthetic chest X-ray images using ACGAN & Diffusion models
- Evaluating realism of generated images
- Assessing whether synthetic images preserve diagnostic features

This work is part of a bachelor thesis at Leiden University.

---

## 🧪 Methods

### Model
- Auxiliary Classifier GAN (ACGAN)
- DDPM

### Tasks
- Train generator and discriminator on chest X-ray dataset
- Generate synthetic COVID-19 images
- Evaluate using:
  - Visual inspection
  - Classification performance
  - (Optional) FID score

---

## 📂 Dataset

- Curated COVID-19 Chest X-ray Dataset (Kaggle)

Classes:
- Normal
- COVID-19
- Pneumonia

> ⚠️ Dataset is not included in this repository due to size constraints. The Pneumonia datasets are not used in this project.
