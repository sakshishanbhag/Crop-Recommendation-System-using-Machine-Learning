# 🌱 Crop Recommendation System using Machine Learning

## 📌 Overview

The Crop Recommendation System is a machine learning-based web application that helps users determine the most suitable crop to grow based on soil and environmental conditions.

The system takes input parameters such as Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, and Rainfall, processes them using trained ML models, and provides the best crop recommendation.

---

## 🚀 Features

* 🌾 Predicts the most suitable crop based on input data
* 📊 Uses trained machine learning models for accurate predictions
* ⚡ Real-time prediction through a Flask web app
* 🎯 Simple and user-friendly interface
* 🔄 Data scaling using MinMaxScaler and StandardScaler

---

## 🧠 Machine Learning Workflow

* Data preprocessing and cleaning
* Feature scaling using MinMaxScaler and StandardScaler
* Model training using Scikit-learn
* Model serialization using Pickle
* Real-time inference through Flask backend

---

## 🛠️ Technologies Used

* Python
* Flask
* Scikit-learn
* Pandas
* NumPy
* HTML, CSS, Bootstrap

---

## 📂 Project Structure

```
├── app.py
├── model.pkl
├── minmaxscaler.pkl
├── standscaler.pkl
├── templates/
│   └── index.html
├── Crop_recommendation.csv
├── Crop Classification With Recommendation System.ipynb
└── README.md
```

---

## ⚙️ How It Works

1. User enters soil and climate parameters in the web interface
2. Data is collected and converted into a feature array
3. Features are scaled using:

   * MinMaxScaler
   * StandardScaler
4. The trained ML model predicts the crop
5. Result is displayed on the UI

From your backend logic: 

---

## ▶️ Installation & Setup

### 1. Clone the repository

```
git clone https://github.com/your-username/crop-recommendation-system.git
cd crop-recommendation-system
```

### 2. Install dependencies

```
pip install -r requirements.txt
```

### 3. Run the application

```
python app.py
```

### 4. Open in browser

```
http://localhost:5000
```

---

## 🖥️ User Interface

The application provides an interactive UI where users can input:

* Soil nutrients (N, P, K)
* Temperature
* Humidity
* pH level
* Rainfall

The frontend is built using Bootstrap with responsive design. 

---

## 🌾 Supported Crops

The system can recommend crops such as:

* Rice
* Maize
* Cotton
* Mango
* Banana
* Coffee
* Chickpea
* Watermelon
* Grapes
* And more

---

## 📈 Future Improvements

* Integration with real-time weather APIs
* Mobile application support
* Market price-based recommendations
* Advanced deep learning models
* Multi-language support for farmers

---
