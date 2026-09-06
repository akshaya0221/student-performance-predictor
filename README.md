# Student Performance Predictor Using Deep Learning with TensorFlow

## Project Overview

This project predicts a student's final academic score using a TensorFlow neural network.

The model uses student-related factors such as study hours, attendance, previous exam score, assignment score, sleep hours, and participation score to predict the final score.

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab

## Dataset

The dataset contains 1,000 student records.

### Input Features

- Study Hours
- Attendance
- Previous Score
- Assignment Score
- Sleep Hours
- Participation Score

### Output

- Final Score

## Machine Learning Approach

This project uses a **Deep Learning Regression model** built with TensorFlow/Keras.

### Neural Network Architecture

- Input layer: 6 features
- Hidden layer: 64 neurons, ReLU
- Hidden layer: 32 neurons, ReLU
- Output layer: 1 neuron

The model uses:

- Adam optimizer
- Mean Squared Error (MSE) loss
- Mean Absolute Error (MAE) metric

## Model Evaluation

The model was evaluated using:

- MAE
- MSE
- RMSE
- R² Score

Approximate results:

- MAE: 4.87
- RMSE: 6.05
- R² Score: 0.67

## Project Features

- Dataset creation
- Data analysis
- Data visualization
- Feature scaling
- TensorFlow neural network
- Model training
- Model evaluation
- Actual vs predicted comparison
- New student prediction
- User-input prediction
- Trained model saving

## Files

- `student-performance-predictor.ipynb` — Complete project notebook
- `student_performance.csv` — Dataset
- `student_performance_model.keras` — Trained TensorFlow model

## Team Members

Tuduru Akshaya
Janga Harshitha
Pinninte Rithika Reddy
Pamireddy Chandravathi

