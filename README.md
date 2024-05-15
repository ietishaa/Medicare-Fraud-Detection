# Medicare Fraud Detection System

## Overview
This project aims to develop a Medicare Fraud Detection System using PySpark. The system analyzes Medicare claims data to identify potentially fraudulent activities using machine learning techniques.

## Table of Contents
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Structure
The project is divided into two main parts:

1. **Data Preprocessing:**
   - In this part, the Medicare claims data is loaded into a PySpark DataFrame.
   - Data cleaning, preprocessing, and feature engineering are performed.
   - Missing values are imputed, and categorical variables are encoded.
   - Exploratory Data Analysis (EDA) is conducted to understand the data distribution and correlations.
   
2. **Model Building and Evaluation:**
   - A logistic regression model is built using PySpark's machine learning library.
   - The model is trained on the preprocessed data to predict fraudulent Medicare claims.
   - Evaluation metrics such as Area Under ROC Curve and accuracy are calculated.
   - An example data point is used to demonstrate model predictions.

## Requirements
- Python 3.x
- PySpark
- Pandas
- Matplotlib
- Seaborn

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/medicare-fraud-detection.git
   ```
2. Install the required dependencies:
   ```bash
   pip install pyspark pandas matplotlib seaborn
   ```

## Usage
1. **Data Preprocessing:**
   - Open `data_preprocessing.ipynb` in Jupyter Notebook or any compatible environment.
   - Execute the cells to preprocess the Medicare claims data.
   - Explore the data and visualize distributions and correlations.
   
2. **Model Building and Evaluation:**
   - Open `model_building.ipynb` in Jupyter Notebook or any compatible environment.
   - Execute the cells to build and evaluate the logistic regression model.
   - Adjust model parameters and threshold values as needed.

## Results
- The Medicare Fraud Detection System achieves high performance with an Area Under ROC Curve of 1.0000 and an accuracy of 0.9984 on the test data.
- The logistic regression model effectively identifies potentially fraudulent Medicare claims.

## Contributing
Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request.

