# Gym Member Exercise Prediction

This project demonstrates machine learning models to analyze and predict gym member exercise patterns using Python.

## Project Structure
- [`Prediction_using_function.ipynb`](./Prediction_using_function.ipynb) - Implementation using modular functions
- [`Prediction_without_function.ipynb`](./Prediction_without_function.ipynb) - Direct implementation without functions
- [`Prediction_with_user_input.ipynb`](./Prediction_with_user_input.ipynb) - Interactive implementation allowing user input

## Dependencies
- NumPy
- Pandas 
- Matplotlib
- PyTorch
- Scikit-learn
- StandardScaler

## Dataset
The project uses a gym members exercise tracking dataset accessed from:
`https://raw.githubusercontent.com/sayande01/Kaggle_Notebooks/refs/heads/main/gym_members_exercise_tracking.csv`

## Features
- Data preprocessing and standardization
- Linear regression model implementation using PyTorch
- Model evaluation metrics (MSE, MAE, R-squared)
- Data visualization of predictions vs actual values
- User input interface for real-time predictions

## Model Features
The model predicts calories burned based on:
- Age
- Weight (kg)
- Height (m)  
- Max BPM
- Average BPM
- Resting BPM
- Session Duration (hours)
- Fat Percentage
- Water Intake (liters)
- Workout Frequency (days/week)
- Experience Level
- BMI

## Usage
1. Open notebooks in Jupyter/Google Colab
2. Run cells sequentially to:
   - Load and preprocess data
   - Train the prediction model 
   - Evaluate model performance
   - Make predictions
3. Use `Prediction_with_user_input.ipynb` to input custom values and get predictions

## Implementations
The project provides three different approaches:
1. Modular approach with functions for better code organization
2. Direct implementation for simpler understanding
3. Interactive implementation with user input functionality

## Model Performance
- Mean Squared Error (MSE): ~2100
- Mean Absolute Error (MAE): ~36
- R-squared (R²): ~0.97