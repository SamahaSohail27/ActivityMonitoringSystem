# Human Activity Recognition using Sensor Data

## Overview

This project focuses on classifying human activities using sensor data collected from various sources, including accelerometers, gyroscopes, and magnetometers. The classification is performed using machine learning algorithms, specifically RandomForestClassifier and Support Vector Classifier (SVC).

## Table of Contents

- [Features](#features)
- [Results](#results)
- [Getting Started](#getting-started)
- [License](#license)

## Features

- **Data Preprocessing:**
  - Z-score normalization is applied to standardize the features.
  - Various sensor data sources are used, such as accelerometers, gyroscopes, and magnetometers.

- **Feature Extraction:**
  - Statistical features (mean, max, min, std, var, median, percentile) are extracted to create feature vectors for classification.

- **Machine Learning Models:**
  - RandomForestClassifier and SVC are employed for activity classification.

- **SHAP Values:**
  - SHAP (SHapley Additive exPlanations) values are calculated to interpret the impact of each feature on the model's output.

## Results

### Random Forest

- **Confusion Matrix:**
  ```
  [[39  0  0 ...  0  0  0]
   [ 0 49  0 ...  0  0  0]
   [ 0  9 17 ...  0  3  0]
   ...
   [ 1  4  1 ... 19  0  0]
   [ 0  0  0 ...  0 36  0]
   [ 0  0  0 ...  0  0 30]]
  ```

- **Accuracy:** 64.12%
- **Average F1-score:** 0.64
- **Recall:** 63.99%

### Support Vector Classifier

- **Confusion Matrix:**
  ```
  [[39  0  0 ...  0  0  0]
   [ 0 46  2 ...  0  1  0]
   [ 0  5 22 ...  2  0  0]
   ...
   [ 2  4  3 ... 11  0  0]
   [ 0  0  0 ...  0 31  0]
   [ 0  0  0 ...  0  0 29]]
  ```

- **Accuracy:** 55.77%
- **Average F1-score:** 0.55
- **Recall:** 56.04%

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the main script:**
   ```bash
   python main.py
   ```

Feel free to explore the code, contribute, or provide feedback!


