# 🎵 Emotion Regression in Music

This repository contains the complete code, model training pipeline, and visualizations for predicting **arousal** and **valence** from music using a hybrid deep learning approach.

## 📌 Project Highlights

- Regression-based emotion modeling using the DEAM dataset
- Deep learning models: CNNs, CNN+GRU, GRU+Attention
- Hybrid pipeline using PANNs pretrained audio embeddings
- Evaluation on standard regression metrics (R², RMSE, MAE)
- Visualizations: t-SNE, training curves, architecture diagrams

## 📂 Structure

- `data/`: Processed audio features & labels
- `notebooks/`: Analysis & visualizations
- `report/`: Final research report PDF

## 📦 Setup

```bash
git clone https://github.com/<your_username>/emotion-regression-music.git
cd emotion-regression-music
pip install -r requirements.txt
