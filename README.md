# Soil Moisture Prediction using Machine Learning, CNN & Transformer Models

## Overview

This project focuses on predicting soil moisture in crop agroecosystems using Machine Learning and Deep Learning techniques. The system utilizes biometeorological and eddy flux tower data to build predictive models capable of estimating soil moisture accurately.

The project compares the performance of traditional Machine Learning models with advanced Deep Learning architectures, including CNN and Transformer models, to improve prediction capability and temporal feature learning.

---

## Objectives

* Predict soil moisture using environmental and biometeorological data.
* Compare the performance of multiple ML and DL models.
* Improve prediction learning using CNN and Transformer architectures.
* Evaluate model robustness using cross-validation techniques.
* Visualize prediction accuracy using regression and hexbin plots.

---

## Models Implemented

### Machine Learning Models

* Random Forest (RF)
* Extreme Gradient Boosting (XGBoost)
* Support Vector Machine (SVM)

### Deep Learning Models

* Artificial Neural Network (ANN / MLP)
* Deep Neural Network (DNN)
* Long Short-Term Memory (LSTM)
* Convolutional Neural Network (CNN)
* Transformer Model

---

## Novel Contribution

This project extends traditional soil moisture prediction systems by integrating CNN and Transformer-based architectures to better capture spatial-temporal relationships and complex environmental patterns from agroecosystem data.

---

## Dataset

The dataset contains:

* Soil moisture measurements
* Biometeorological parameters
* Environmental sensor data
* Eddy flux tower observations

### Example Features

* Air Temperature
* Relative Humidity
* Soil Temperature
* Solar Radiation
* Wind Speed
* Vapor Pressure Deficit
* Net Radiation

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* TensorFlow / Keras
* XGBoost
* SciKeras

---

## Project Workflow

### 1. Data Preprocessing

* Removed missing values
* Feature selection
* Data normalization using MinMaxScaler

### 2. Model Training

* Trained multiple ML and DL models
* Applied 10-Fold Cross Validation
* Hyperparameter tuning

### 3. Model Evaluation

Models were evaluated using:

* R² Score
* RMSE (Root Mean Square Error)

### 4. Visualization

* Hexbin plots
* Regression line analysis
* 1:1 comparison plots

### 5. Export Results

* Exported actual and predicted values into CSV format

---

## Performance Metrics

The following metrics were used for model evaluation:

### R² Score

Measures how well predictions fit actual values.

### RMSE

Measures prediction error magnitude.

---

## Folder Structure

```bash
soil-moisture-prediction-ml-dl/
│
├── data/
│   ├── raw_data.csv
│   └── processed_data.csv
│
├── notebooks/
│   └── soil_moisture_prediction.ipynb
│
├── models/
│   ├── rf_model.pkl
│   ├── xgb_model.pkl
│   ├── lstm_model.h5
│   ├── cnn_model.h5
│   └── transformer_model.h5
│
├── results/
│   ├── predictions.csv
│   └── metrics.csv
│
├── plots/
│   ├── hexbin_rf.png
│   ├── hexbin_lstm.png
│   └── model_comparison.png
│
├── requirements.txt
├── README.md
└── main.py
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/soil-moisture-prediction-ml-dl.git
```

### Navigate to Project Folder

```bash
cd soil-moisture-prediction-ml-dl
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Required Packages

```bash
pandas
numpy
matplotlib
scikit-learn
xgboost
tensorflow
scikeras
```

---

## How to Run

### Run Python Script

```bash
python main.py
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
soil_moisture_prediction.ipynb
```

---

## Output

The project generates:

* Prediction CSV files
* Performance metrics
* Hexbin visualization plots
* Model comparison graphs

---

## Visualization

The hexbin plots compare:

* Actual Soil Moisture
* Predicted Soil Moisture

Each plot contains:

* Regression Line
* 1:1 Reference Line
* R² Value
* RMSE Value

---

## Applications

* Smart Agriculture
* Precision Farming
* Water Resource Management
* Irrigation Optimization
* Environmental Monitoring

---

## Future Enhancements

* Real-time IoT sensor integration
* Deployment using Flask or FastAPI
* Cloud-based prediction system
* Mobile application integration
* Advanced attention-based architectures

---

## Results

The Transformer and CNN-based models demonstrated improved capability in learning complex environmental relationships compared to traditional machine learning approaches.

---

## Author

Ranjith Karthala

---

## License

This project is developed for educational and research purposes.
