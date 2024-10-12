# Network Intrusion Detection System

## Overview
The Network Intrusion Detection System (NIDS) project aims to identify and classify network intrusions using machine learning techniques. The system processes a dataset containing over 100,000 rows and 1,527 features, including IP addresses and TCP connections, to effectively detect potential security threats.

## Features
- Processes large datasets with network-related data.
- Normalizes data and applies Principal Component Analysis (PCA) for dimensionality reduction.
- Trains multiple machine learning models, including:
  - Decision Tree
  - Linear SVC
  - Deep Neural Networks
- Achieves 99% accuracy in classifying network intrusions.
- Implements an autoencoder for enhanced anomaly detection.

## Dataset
- **Size**: 100,000+ rows and 1,527 columns
- **Features**: Includes information such as IP addresses, TCP connections, and protocol usage.

## Technologies Used
- **Programming Languages**: Python
- **Libraries**: Scikit-learn, TensorFlow, Pandas, NumPy
- **Techniques**: PCA, Machine Learning, Deep Learning