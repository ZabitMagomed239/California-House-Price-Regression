California House Price Prediction

# Overview

This project uses the California Housing Dataset to build regression models for predicting the median house value based on features such as:

Longitude

Latitude

Total rooms

Total bedrooms

Population

Housing age

Median income

Two machine learning models were implemented:

Linear Regression

Random Forest Regressor

The best-performing model was the default Random Forest Regressor, which achieved a score of 0.8162.


# Dataset Information

Source: California Housing Dataset

Rows: 20,640

Columns: 10

Target variable: median_house_value

## Key features include:

longitude

latitude

housing_median_age

total_rooms

total_bedrooms

population

households

median_income

# Exploratory Data Analysis

The notebook includes:

Summary statistics

Correlation analysis

Heatmaps

Distribution plots

Handling missing values

Feature-target relationships

# Modeling Approach

The following models were implemented and evaluated:

1. Linear Regression

Used as a baseline regression model.

2. Random Forest Regressor (default parameters)

This model delivered the best performance.

# Project Structure

project/
│── .gitignore│── Clifornia.ipynb
│── README.md
│── housing.csv
│── requirements.txt


# Installation

Clone the repository:

$ git clone https://github.com/yourusername/California-House-Price-Regression.git
$ cd California-House-Price-Regression

### Create a virtual environment
$ python -m venv .venv

### Activate the virtual environment
# Windows
$ .venv\Scripts\activate

### macOS / Linux
$ source .venv/bin/activate

### Deactivate the environment
$ deactivate

### Install dependencies:

$ pip install -r requirements.txt

Open using either jupyter notebook or visual code studio

## Libraries Used

numpy==2.4.1
pandas==3.0.0
matplotlib==3.10.8
seaborn==0.13.2
plotly==6.5.2
scikit-learn==1.8.0
