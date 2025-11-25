# Crop Yield & Fertilizer Prediction App

A lightweight Crop Yield and Fertilizer Recommendation system with a Gradio GUI. Predicts crop yield and suggests fertilizer based on soil parameters, weather features, and historical yield data.

## Key features
- Input soil parameters (pH, N, P, K), weather features, crop type
- Predict crop yield (regression model)
- Suggest fertilizer dose and type (rule-based or model-backed)
- Interactive Gradio demo for quick experimentation
- Notebook with EDA and model training pipeline

## Tech stack
- Python (pandas, scikit-learn, xgboost/lightgbm)
- GUI: Gradio
- Notebooks for data exploration and model training
- Optional: Streamlit or simple Flask UI for deployment
- Dockerfile included for containerized deployment

## Quick start (dev)
1. Unzip and open project:
   ```bash
   unzip "/mnt/data/crop yield app-20251117T161133Z-1-001.zip" -d crop-yield-predictor
   cd crop-yield-predictor
   python -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
