# 🤖 Building AI Agents with Multimodal Models – Assessment

This repository contains my completed assessment for the **"Building AI Agents with Multimodal Models"** course by **NVIDIA**, as part of the **MASSAI 2025** summer school.

## 🧪 Assessment Overview

In this task, I was challenged to **transition a classification model** from using **LiDAR data** to using **RGB images** instead. The goal was to pre-train a model using contrastive learning with paired LiDAR and RGB data generated from **NVIDIA Omniverse**.

### 📌 Objective:
Develop a contrastive model called `CILP` (**Contrastive Image LiDAR Pre-training**) capable of learning rich representations from paired sensor data and applying them to an image classification task.

## ✅ Key Steps

- Designed and implemented the `CILP` architecture for contrastive learning.
- Used simulated paired RGB and LiDAR datasets.
- Trained embeddings using contrastive loss.
- Visualized and evaluated performance on classification downstream tasks.
- Compared results to a baseline LiDAR-only classifier.

## 🛠️ Tools & Libraries Used

- Python
- PyTorch
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- NVIDIA Omniverse dataset (simulated)

