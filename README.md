# Cryptocurrency Data Science Project 🚀

## Cryptocurrency Scam Insights Project 🕵️‍♂️

![Cryptocurrency Scam Insights](https://img.shields.io/badge/Cryptocurrency-Scam%20Insights-blueviolet?style=for-the-badge)  
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)  
![License](https://img.shields.io/badge/License-MIT-green)  
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

Welcome to the **Cryptocurrency Data Science Project**! This repository is dedicated to analyzing cryptocurrency data to uncover insights into potential scams using advanced machine learning techniques. Whether you're a data scientist, a crypto enthusiast, or just curious about scam detection, this project provides a comprehensive pipeline for data processing, modeling, and evaluation.

---

## 📖 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Models](#models)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Project Overview 🌟

This project leverages data science and machine learning to identify and predict cryptocurrency scams. By analyzing patterns in cryptocurrency-related data, we aim to provide actionable insights to protect users from fraudulent activities. The pipeline includes data cleaning, feature engineering, model training, and evaluation.

### Key Objectives
- 🔍 Detect potential scams in cryptocurrency transactions.
- 🛠️ Build and evaluate machine learning models for scam prediction.
- 📊 Provide insights into features that indicate fraudulent behavior.

---

## Features ✨

- **Data Cleaning** 🧹: Preprocessing scripts to handle raw cryptocurrency data (`clean_data.csv`).
- **Feature Engineering** 🔧: Extract meaningful features from URLs and transaction data (`uris.csv`).
- **Machine Learning Models** 🤖:
  - Address Prediction (`address_prediction_model.pkl`)
  - Classification Model (`classification_model.pkl`)
  - Clustering Model (`clustering_model.pkl`)
  - Gradient Boosting for Phishing (`gradient_boosting_phishing.pkl`)
  - Logistic Regression for Phishing (`logistic_regression_phishing.pkl`)
  - Random Forest for Phishing (`random_forest_phishing.pkl`)
- **Additional Data** 📂: Includes processed datasets like `df_data.pkl` for further analysis.

---

## Dataset 📈

The project uses the following datasets:
- **`urls.csv`**: URL data for phising detection and feature extraction.
- **`uris.csv`**: URL data for phishing detection and feature extraction.

### Potential Features to Explore
- Transaction frequency and volume
- Wallet address reuse patterns
- URL characteristics (e.g., typosquatting, domain age)
- Social media mentions or sentiment (if external data is integrated)

> **Note**: You can expand the dataset by integrating blockchain data from sources like Etherscan or Bitcoin blockchain APIs.

---

## Models 🧠

This project implements a variety of machine learning models to tackle scam detection:
- **Address Prediction Model** (`address_prediction_model.pkl`): Predicts suspicious wallet addresses.
- **Classification Model** (`classification_model.pkl`): Classifies transactions as legitimate or fraudulent.
- **Clustering Model** (`clustering_model.pkl`): Groups similar transactions to identify scam patterns.
- **Gradient Boosting for Phishing** (`gradient_boosting_phishing.pkl`): Detects phishing URLs using gradient boosting techniques.
- **Logistic Regression for Phishing** (`logistic_regression_phishing.pkl`): A baseline model for phishing detection.
- **Random Forest for Phishing** (`random_forest_phishing.pkl`): An ensemble model for improved phishing detection accuracy.

All models are saved as `.pkl` files for easy reuse and deployment.

---
