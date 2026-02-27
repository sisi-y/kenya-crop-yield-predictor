🌽 Kenya Crop Yield Predictor

A machine learning project that predicts maize crop yield for Kenyan farms using rainfall, fertiliser usage, and farm size.

This project demonstrates a complete machine learning workflow:
data preparation → model training → evaluation → visualisation → prediction.

📌 Project Overview

The model uses Multiple Linear Regression to estimate crop yield (in kilograms) based on:

Rainfall (mm)

Fertiliser used (kg)

Farm size (acres)

The dataset contains 300 synthetic Kenyan farm records.

📊 Model Performance

Algorithm: Linear Regression

R² Score: ~97%

Evaluation Metrics:

R² Score

Mean Absolute Error (MAE)

The model explains approximately 97% of the variation in crop yield within the dataset.

📈 Features Used
Feature	Description
Rainfall_mm	Annual rainfall received
Fertiliser_kg	Fertiliser applied per season
Farm_Size_acres	Total cultivated land area
🛠 Tech Stack

Python 3

Pandas

NumPy

Scikit-learn

Matplotlib

Google Colab

▶️ How to Run

Clone this repository

Install dependencies:

pip install pandas numpy scikit-learn matplotlib

Run the notebook or Python script.

🔍 What This Project Demonstrates

Train/test data splitting

Model training using Linear Regression

Model evaluation using R² and MAE

Feature importance analysis

Custom prediction function for new farms

Data visualisation

🚀 Future Improvements

Use real agricultural datasets

Add more features (soil quality, temperature, seed variety)

Deploy as a web application for farmers

👩‍💻 Author

Wangari Njoroge
ML Engineer in Training
BSc Actuarial Science
