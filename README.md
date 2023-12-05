# Cab Price Prediction ML Project

## Overview

This project implements a machine learning model to predict cab prices using historical cab ride data and weather information. The model is designed to analyze patterns in the data to make accurate fare predictions for future cab rides.

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Description

The primary goal of this project is to create a predictive model that estimates cab prices based on various factors, including historical cab ride data and weather conditions. The model aims to provide accurate fare predictions for the benefit of both cab companies and passengers.

## Features

- Utilizes historical cab ride data.
- Incorporates weather information for more accurate predictions.
- Predicts cab prices based on various input parameters.
- User-friendly interface for inputting ride details and obtaining fare estimates.

## Dataset

The dataset used for this project includes historical cab ride data and weather information. The cab ride data contains details such as distance traveled, time of day, and other relevant factors. Weather information includes parameters like temperature, precipitation, and wind speed.

## Dependencies

This project requires the following dependencies:

- Python (>=3.6)
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

You can install these dependencies using the provided `requirements.txt` file.

## Installation

1. Clone the repository:

   ```bash
   https://github.com/Framework12/UBER_Cab_price_prediction_model.git

## Navigate to the project directory
cd cab-price-prediction

## Install the dependencies
pip install -r requirements.txt

## Usage

Run the application
python app.py

Input the relevant details, such as distance, time, and weather conditions.
Obtain the predicted cab fare.

## Model Training

If you want to train the model with your own data:

Replace the existing dataset with your data in the data directory.

Modify the data preprocessing and model training scripts as needed.

Run the training script:

python train_model.py

## Evaluation

The model's performance can be evaluated using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). The evaluation results are displayed during the model training process.

## Results
The results of the model predictions, as well as evaluation metrics, are stored in the results directory.

## License
This project is licensed under the MIT License.
