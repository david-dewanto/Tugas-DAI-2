# DAI Assignment 2 - Phishing URL Detection
Group 18

## Overview
This repository contains code for a machine learning project that detects phishing URLs using K-Nearest Neighbors (KNN) and Naive Bayes algorithms implemented from scratch. The project focuses on building and comparing these two fundamental machine learning algorithms to identify potentially malicious URLs.

## Features
- Implementation of KNN and Naive Bayes algorithms from scratch
- Comprehensive data preprocessing pipeline
- Model evaluation and comparison
- Hyperparameter tuning
- Performance analysis
- Kaggle competition submission generation

## Requirements
- Anaconda
- Python libraries:
  - category_encoders
  - numpy
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn
  - jupyter

## Installation & Setup
1. Install Anaconda on your system from [Anaconda's website](https://www.anaconda.com/download)
2. Open Anaconda Prompt
3. Install the required library:
```bash
conda install -c conda-forge category_encoders
```

## Running the Code
1. Clone this repository
2. Open Jupyter Notebook:
```bash
jupyter notebook
```
3. Navigate to and open the .ipynb file
4. Run all cells sequentially

## Project Structure
- Data Preprocessing
  - Missing value handling
  - Feature scaling
  - Feature engineering
  - Data validation
- Model Implementation
  - K-Nearest Neighbors (KNN) from scratch
  - Naive Bayes from scratch
- Model Evaluation
  - Performance metrics
  - Cross-validation
  - Hyperparameter tuning
- Results Analysis
  - Confusion matrix
  - Classification reports
  - Performance comparison
- Kaggle Submission
  - Prediction generation
  - Submission file creation

## Results
Both models show strong performance in detecting legitimate URLs but have different strengths:
- KNN: Better overall accuracy with balanced precision and recall
- Naive Bayes: Faster training and prediction times with comparable accuracy

## Others
This is an academic project for the Foundations of Artificial Intelligence course. 