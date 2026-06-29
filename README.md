# SmartTrafficAI 🚦

An AI-powered traffic congestion prediction and analytics system that leverages machine learning to predict traffic conditions, visualize road congestion, and provide intelligent recommendations for urban traffic management.

## Features

* 🚗 Real-time traffic congestion prediction
* 📊 Interactive dashboard with analytics
* 🤖 Machine Learning-based prediction model
* 📈 Traffic trend visualization
* 🚦 Lane-wise traffic monitoring
* 💡 AI-powered traffic management recommendations
* ⚡ FastAPI backend with REST APIs
* 🎨 React.js frontend for an interactive user interface

## Tech Stack

### Frontend

* React.js
* Vite
* HTML5
* CSS3
* JavaScript

### Backend

* FastAPI
* Python
* Pandas
* NumPy
* Scikit-learn
* Joblib

### Machine Learning

* Random Forest Classifier
* Feature Engineering
* Data Preprocessing
* Model Evaluation

## Project Structure

```
SmartTrafficAI/
│
├── backend/
├── frontend/
├── data/
├── outputs/
├── notebooks/
├── docs/
├── README.md
├── requirements.txt
└── .gitignore
```

## Installation

### Clone the repository

```bash
git clone https://github.com/Nireeksha-Naik/SmartTrafficAI.git
cd SmartTrafficAI
```

### Backend Setup

```bash
pip install -r requirements.txt
```

Run the backend server:

```bash
uvicorn backend.app:app --reload
```

Backend URL:

```
http://127.0.0.1:8000
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend URL:

```
http://localhost:5173
```

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Model Training
5. Model Evaluation
6. Traffic Prediction
7. Recommendation Generation

## Dataset

The project uses traffic sensor data containing:

* Vehicle Count
* Average Speed
* Queue Delay
* Occupancy Rate
* Date & Time Features
* Lane-wise Traffic Information

## Results

* High prediction accuracy using Machine Learning
* Real-time congestion prediction
* AI-generated traffic recommendations
* Interactive visualization dashboard

## Future Improvements

* Live IoT sensor integration
* Google Maps API integration
* Real-time GPS data
* Deep Learning models
* Cloud deployment
* Mobile application

## Contributors

**Nireeksha P**

## License

This project is intended for educational and research purposes.
