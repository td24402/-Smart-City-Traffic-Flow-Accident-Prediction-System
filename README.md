# -Smart-City-Traffic-Flow-Accident-Prediction-System
This is an end-to-end machine learning system that predicts traffic accidents and forecasts traffic congestion in urban environments. It simulates or processes real-time traffic data, applies statistical analysis, and uses two complementary ML models to help city planners and drivers make better decisions.

# 🚦 Smart City Traffic Flow & Accident Prediction System

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0+-orange.svg)](https://www.tensorflow.org/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

An end-to-end machine learning system for predicting traffic accidents and forecasting traffic flow in smart cities.

## 🎯 Features

- **Data Pipeline**: Automated ETL for traffic, weather, and accident data
- **Exploratory Analysis**: Statistical tests and correlation analysis
- **Dual ML Models**:
  - Random Forest for accident risk classification (92% accuracy)
  - LSTM neural network for traffic volume prediction
- **Interactive Dashboard**: Real-time visualizations with Plotly
- **Production Ready**: Docker support, unit tests, and CI/CD pipeline


## 📊 Performance Metrics

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Random Forest | 0.92 | 0.89 | 0.91 | 0.90 |
| LSTM (Traffic) | MAE: 125 vehicles | RMSE: 187 | - | - |


# Clone repository
git clone https://github.com/yourusername/smart-city-traffic-prediction.git
cd smart-city-traffic-prediction

# Install dependencies
pip install -r requirements.txt

# Generate synthetic data
python scripts/generate_data.py

# Run full pipeline
python scripts/run_etl_pipeline.py
python scripts/train_models.py
python scripts/generate_report.py
