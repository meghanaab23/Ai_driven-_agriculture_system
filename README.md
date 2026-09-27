# 🌱 AI Driven Smart Agriculture System

An AI-powered smart agriculture system that uses **Machine Learning, IoT-based sensor data, and data-driven recommendations** to help farmers make better decisions about crops, soil health, irrigation, fertilizer usage, and crop yield.

The system analyzes agricultural and environmental data and provides intelligent recommendations through a user-friendly application.

---

## 🚀 Features

### 🌾 Crop Recommendation
Recommends suitable crops based on agricultural and environmental conditions such as:

- Nitrogen
- Phosphorus
- Potassium
- Temperature
- Humidity
- Soil pH
- Rainfall

### 💧 Smart Irrigation Prediction
Predicts irrigation requirements using environmental and soil-related parameters.

The system uses a Machine Learning model to determine whether irrigation is required.

### 🧪 Soil Health Prediction
Analyzes soil parameters and classifies soil health into:

- Healthy
- Moderate
- Poor

### 🌱 Fertilizer Recommendation
Provides fertilizer recommendations based on soil nutrient conditions and crop-related information.

### 📈 Crop Yield Prediction
Predicts expected crop yield using historical agricultural data and relevant crop and environmental parameters.

### 🦠 Crop Disease Detection
The project also includes an AI-based crop disease detection module for identifying plant diseases from crop images.

---

## 🧠 Machine Learning Models

The project contains multiple trained Machine Learning models:

| Model | Algorithm | Purpose |
|---|---|---|
| Crop Recommendation | Random Forest | Recommend suitable crops |
| Irrigation Prediction | Random Forest | Predict irrigation requirements |
| Soil Health | Random Forest | Classify soil health |
| Fertilizer Recommendation | Random Forest | Recommend fertilizer |
| Crop Yield Prediction | Random Forest | Predict crop yield |
| Crop Disease Detection | Deep Learning | Detect crop diseases |

---

## 📊 Model Performance

The models were trained using agricultural datasets.

| Model | Accuracy / Metric |
|---|---:|
| Irrigation Model | **99.91% Accuracy** |
| Crop Recommendation | **92.25% Accuracy** |
| Fertilizer Recommendation | **92.00% Accuracy** |
| Soil Health Prediction | **87.65% Accuracy** |
| Crop Yield Prediction | **R² = 0.9710** |

> Model performance can vary depending on the dataset, preprocessing, and training configuration.

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Machine Learning
- Scikit-learn
- Random Forest
- TensorFlow / Keras

### Data Processing
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn

### Web Application
- Flask / Python backend
- HTML
- CSS
- JavaScript

### Database / Storage
- MySQL
- CSV datasets

### Development Tools
- Visual Studio Code
- Jupyter Notebook
- Git
- GitHub
- Git LFS

---

## 📁 Project Structure

```text
AI Driven Smart Agriculture
│
├── ai-smart-agriculture-main
│   │
│   ├── backend
│   │   ├── app
│   │   │   ├── ml_models
│   │   │   │   ├── saved_models
│   │   │   │   │   ├── crop_random_forest.pkl
│   │   │   │   │   ├── crop_yield_random_forest.pkl
│   │   │   │   │   ├── fertilizer_random_forest.pkl
│   │   │   │   │   └── soil_random_forest.pkl
│   │   │   │   │
│   │   │   │   ├── irrigation_model.pkl
│   │   │   │   ├── irrigation_scaler.pkl
│   │   │   │   └── training scripts
│   │   │   │
│   │   │   ├── routes
│   │   │   ├── services
│   │   │   └── ...
│   │   │
│   │   ├── datasets
│   │   └── requirements.txt
│   │
│   ├── frontend
│   │   ├── HTML
│   │   ├── CSS
│   │   └── JavaScript
│   │
│   └── ...
│
├── README.md
└── .gitattributes
