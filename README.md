# Earthquake-Induced Damage Grade Prediction

This repository contains the code and dataset used in developing an optimal machine learning model for predicting earthquake-induced damage grades (ranging from 0 to 4) based on data from the 2015 Nepal (Gorkha) Earthquake. The project aims to provide accurate predictions of building damage, assisting in post-disaster assessments and future risk management.

## Key Features

- **Data Source**: 
  - The dataset includes structural damage data collected during the 2015 Gorkha Earthquake.
  - Earthquake intensity data is provided in contour form, and **linear interpolation** was used to estimate intensities for specific locations (wards).

- **Damage Grade Prediction**: 
  - The damage grades are categorized from 0 (no damage) to 4 (complete destruction).
  - The classification allows for a comprehensive assessment of damage severity for various structures.

- **Machine Learning Models**: 
  - Several machine learning models were tested to identify the most suitable one for predicting damage grades.
  - This repository includes code for training, testing, and hyperparameter tuning to optimize the model's performance.

- **Linear Interpolation for Intensity Data**: 
  - The available intensity data in contour form was interpolated linearly to determine earthquake intensities at ward-level locations.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/Earthquake-Damage-Grade-Prediction.git
