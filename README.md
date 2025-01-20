# Gym Member Exercise Prediction

This project demonstrates machine learning models to analyze and predict gym member exercise patterns using Python.

## Project Structure
- [`Prediction_using_function.ipynb`](./Prediction_using_function.ipynb) - Implementation using modular functions
- [`Prediction_without_function.ipynb`](./Prediction_without_function.ipynb) - Direct implementation without functions 
- [`Prediction_with_user_input.ipynb`](./Prediction_with_user_input.ipynb) - Interactive implementation allowing user input
- [`Calories_burned_prediction_optimized.ipynb`](./Calories_burned_prediction_optimized.ipynb) - Optimized implementation with improved model architecture

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
- Optimized model architecture with improved performance
- Learning rate tuning and epoch optimization
- Enhanced data visualization for model training progress

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
- Gender
- Workout Type

## Usage
1. Open notebooks in Jupyter/Google Colab
2. Run cells sequentially to:
   - Load and preprocess data
   - Train the prediction model 
   - Evaluate model performance
   - Make predictions
3. Use `Prediction_with_user_input.ipynb` for custom value predictions
4. Use `Calories_burned_prediction_optimized.ipynb` for best performance

## Implementations
The project provides four different approaches:
1. Modular approach with functions for better code organization
2. Direct implementation for simpler understanding
3. Interactive implementation with user input functionality
4. Optimized implementation with enhanced model architecture and performance

## Model Performance
- Mean Squared Error (MSE): ~1560 (improved from ~2100)
- Mean Absolute Error (MAE): ~30 (improved from ~36)
- R-squared (R²): ~0.979 (improved from ~0.97)