# Disease Spread Prediction under Climate Change (Synthetic Data)

This project simulates the impact of climate change on disease spread using machine learning and synthetic data. It demonstrates how various environmental and population-related features can be used to predict disease incidence using a regression model.

## 📁 Files Included

- `synthetic_disease_data.xlsx`: An Excel file containing 1,000 rows of synthetic data, including:
  - Temperature (°C)
  - Humidity (%)
  - Rainfall (mm/month)
  - CO₂ concentration (ppm)
  - Population density (people/km²)
  - Vector presence index (0 to 1)
  - Disease cases (target variable)

- `disease_spread_model.py`: Python script that:
  - Generates synthetic data
  - Trains a Random Forest regression model
  - Evaluates model performance
  - Visualizes feature importance

## 🚀 How to Use

1. **Install Requirements**  
   Make sure Python 3 is installed. Then install required packages:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
Run the Code
Execute the Python script to train and evaluate the model:




python disease_spread_model.py
Explore the Data
Open synthetic_disease_data.xlsx to explore how climate variables influence disease predictions.

🧠 Machine Learning Model
Model Used: Random Forest Regressor

Target Variable: Predicted number of disease cases per 1000 people

Features:

Climate: Temperature, Humidity, Rainfall, CO₂

Demographics: Population Density

Environment: Vector Index

📊 Output
Model evaluation: Mean Squared Error (MSE) and R² score

Feature importance plot

📌 Note
This dataset is synthetically generated for demonstration purposes only and does not represent real-world epidemiological or climate data.

📫 Author 
Tarinabo williamtarinabo@gmail.com
