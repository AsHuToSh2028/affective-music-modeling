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
- `scripts/`: Feature extraction & training code
- `notebooks/`: Analysis & visualizations
- `models/`: Saved weights
- `figures/`: Architecture & t-SNE plots
- `report/`: Final research report PDF

## 📊 Results Snapshot

| Model                  | R² (Valence) | R² (Arousal) |
|------------------------|--------------|--------------|
| CNN Baseline           | 0.554        | 0.483        |
| CNN + SE + Temporal    | 0.464        | 0.527        |
| CNN + GRU              | 0.460        | 0.512        |
| CNN + GRU + Attention  | 0.456        | 0.499        |
| **PANNs + MLP (ours)** | **0.457**    | **0.667**    |

## 📦 Setup

```bash
git clone https://github.com/<your_username>/emotion-regression-music.git
cd emotion-regression-music
pip install -r requirements.txt
