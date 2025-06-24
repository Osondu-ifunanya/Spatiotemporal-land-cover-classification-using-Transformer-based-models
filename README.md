# Spatiotemporal Land Cover Classification Using Transformer Model

This project demonstrates how to classify land cover types using synthetic spatiotemporal satellite data and a Transformer-based deep learning model in Python.

## 📊 Description

Land cover classification is essential for environmental monitoring. This project creates synthetic multitemporal satellite-like data for a 20x20 grid and uses a Transformer neural network to learn temporal features and predict land cover classes.

## 🛠️ Features

- Generates synthetic satellite image time-series data
- Prepares spatiotemporal sequences for each pixel
- Uses PyTorch to build and train a Transformer-based classifier
- Exports predictions with true labels to an Excel file

## 📁 Output

- `spatiotemporal_transformer_landcover.xlsx` — contains `Pixel_ID`, `True_Label`, and `Predicted_Label`

## 🧪 Requirements

Install dependencies with:

```bash
pip install numpy pandas scikit-learn torch openpyxl
