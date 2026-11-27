
# Power Plant Energy Prediction using ANN

## Project Overview
This project predicts the electrical energy output of a Combined Cycle Power Plant using an Artificial Neural Network (ANN) regression model.

The model uses environmental factors to estimate power generation.

## Dataset
The dataset contains the following input features:

- Ambient Temperature (AT)
- Exhaust Vacuum (V)
- Ambient Pressure (AP)
- Relative Humidity (RH)

Target: Net Hourly Electrical Energy Output (PE)

Dataset: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/294/combined+cycle+power+plant)

## Tools and Technologies
- Python
- PyTorch
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Model Architecture
- Input Layer: 4 features
- Hidden Layers: 2 layers with 6 neurons each
- Activation: ReLU
- Optimizer: Adam
- Loss Function: Mean Squared Error (MSE)
- Epochs: 100

## Workflow
1. Data preprocessing and feature scaling
2. Train, validation, and test split
3. ANN model development using PyTorch
4. Model training and validation
5. Model evaluation on test data

## Evaluation Metrics
- Mean Squared Error (MSE)
- R² Score

## Project Structure
```text
Power-Plant-Energy-Prediction/
├── ANN_Regression.ipynb
├── powerplant_data.csv
└── README.md
```

## Author
Ankush Kumar

Aspiring Data Analyst | Machine Learning | Deep Learning
