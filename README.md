# Spam Detector

A simple Flask-based web application that uses machine learning to detect spam messages. This project demonstrates text preprocessing, feature extraction with TF-IDF, handling imbalanced datasets with oversampling (SMOTE), and deploying a model as a web application.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation & Usage](#installation)
## Overview

Spam messages can be a nuisance and a security risk. This project builds a spam detection model using machine learning techniques. The application preprocesses text data (cleaning, tokenization, TF-IDF feature extraction), handles class imbalance using oversampling, and deploys the trained model via a Flask web app where users can input a message and see if it is classified as spam or not.

## Features

- **Text Preprocessing:** Cleans and normalizes input messages.
- **Feature Extraction:** Uses TF-IDF to convert text into numerical features.
- **Imbalanced Data Handling:** Applies oversampling (SMOTE) to boost spam class representation.
- **Machine Learning Model:** Trains a classifier (e.g., Logistic Regression) to differentiate between spam and ham.
- **Web Interface:** A simple Flask application for real-time spam detection.

## Installation

### Prerequisites

- Python 3.x
- [pip](https://pip.pypa.io/en/stable/installation/)

### Steps

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/spam-detector.git
   cd spam-detector

3. **Run the Flask App:**
   open the terminal and run:
   ```bash
   python app.py
  The application will be accessible at [pip](http://127.0.0.1:5000/).
  
