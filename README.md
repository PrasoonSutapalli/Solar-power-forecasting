#  Solar Power Forecasting using Artificial Neural Networks (ANN)

This project predicts solar power generation using a Deep Learning model built with TensorFlow and Keras.  
The model forecasts AC Power Output (Watts) based on environmental and electrical parameters.

---

##  Project Overview

Accurate solar power forecasting helps improve:

- Energy efficiency
- Grid stability
- Renewable energy optimization
- Power management systems

This project implements a Neural Network regression model to predict AC Power output using real-world generation data.

---

##  Model Architecture

The Artificial Neural Network (ANN) consists of:

- Input Layer (8 Features)
- Dense Layer (32 neurons, ReLU activation)
- Dense Layer (16 neurons, ReLU activation)
- Output Layer (1 neuron for power prediction)

Optimizer: Adam  
Loss Function: Mean Squared Error (MSE)  
Epochs: 35  
Batch Size: 32  

---

##  Features Used for Prediction

The model uses the following input features:

- Module Temperature
- Ambient Temperature
- Wind Speed
- Irradiance (W/m²)
- DC Current
- AC Current (R Phase)
- AC Current (Y Phase)
- AC Current (B Phase)

Target Variable:
- AC Power in Watts

---

##  Tech Stack

- Python
- Pandas
- NumPy
- TensorFlow / Keras
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

##  Project Structure

Solar-power-forecasting/
│
├── AI_Solar_Power_Prediction.ipynb
├── generation_data.csv
├── README.md
├── .gitignore
└── LICENSE

---

##  Installation & Setup

1️⃣ Clone the repository:

git clone https://github.com/your-username/Solar-power-forecasting.git

2️⃣ Navigate to the project folder:

cd Solar-power-forecasting

3️⃣ Install dependencies:

pip install pandas numpy matplotlib scikit-learn tensorflow jupyter

4️⃣ Run Jupyter Notebook:

jupyter notebook

Open:
AI_Solar_Power_Prediction.ipynb

---

## Model Workflow

- Data Loading
- Handling Missing Values
- Feature Scaling (StandardScaler)
- Train-Test Split (80/20)
- ANN Model Training
- Loss Curve Visualization
- Actual vs Predicted Power Comparison

---

##  Model Evaluation

The model performance is evaluated using:

- Mean Squared Error (MSE)
- Training & Validation Loss Curves
- Scatter Plot of Actual vs Predicted Power

---

## Future Improvements

- Add R² Score and MAE metrics
- Hyperparameter tuning
- LSTM model for time-series forecasting
- Deploy as a web-based dashboard
- Integrate real-time solar data

---

##  License

This project is licensed under the MIT License.
