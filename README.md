# 🌾 Crop Recommendation System Using Machine Learning

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-Web_App-lightgrey?logo=flask)](https://flask.palletsprojects.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

An intelligent machine learning-based system that predicts the most suitable crop to grow based on soil and weather conditions. It is designed to help farmers and agricultural decision-makers make informed choices to maximize crop yield and optimize resource usage.


---

## 🔍 Features

- ✅ Predicts the best crop based on:
  - Nitrogen (N), Phosphorus (P), Potassium (K)
  - Temperature, Humidity, pH level, Rainfall
- 🧠 Trained using Random Forest Classifier
- 🔄 Preprocessing with MinMaxScaler & StandardScaler
- 🌐 Flask-based web interface
- 🖥️ Simple UI using HTML forms

---

## 📁 Project Structure

```
Crop-Recommendation-System/
├── app.py                  # Main Flask application
├── train_model.py          # Model training script
├── Crop_recommendation.csv # Dataset
├── model.pkl               # Trained ML model
├── minmaxscaler.pkl        # Saved MinMaxScaler
├── standscaler.pkl         # Saved StandardScaler
├── templates/
│   └── index.html          # HTML input form
└── README.md               # This file
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/crop-recommendation-system.git
cd crop-recommendation-system
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install flask pandas numpy scikit-learn
```

### 3. Train the model (only if not already trained)

```bash
python train_model.py
```

### 4. Start the web application

```bash
python app.py
```

Then, open your browser and visit:  
👉 **http://localhost:5000**

---

## 📊 Dataset

- Dataset: [`Crop_recommendation.csv`](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)
- Features:
  - N, P, K (soil nutrients)
  - Temperature, Humidity
  - pH value
  - Rainfall
- Target: Recommended Crop (22 possible classes)

---

## 🛠️ Technologies Used

- **Python**
- **Flask**
- **Scikit-learn**
- **Pandas & NumPy**
- **HTML/CSS**

---

## 💡 Future Enhancements

- 🔗 Integration with real-time weather APIs
- 📈 Crop profitability analysis
- 📱 Mobile app for easy access
- 💬 Multilingual support for farmers



