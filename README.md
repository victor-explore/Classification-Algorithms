# Classification Tasks Implementation

This repository contains implementations of various classification algorithms for both binary and multi-class classification problems.

## Overview

The project implements different classification approaches:
- Normal Distribution Based Classification
- Gaussian Mixture Models (GMM)
- Parzen Window
- K-Nearest Neighbors (KNN)
- Linear Classification

## Binary Classification

### Features
- Data preprocessing and splitting
- Implementation of multiple classification methods
- Performance evaluation using confusion matrices
- ROC curve plotting
- Accuracy and F1-score calculations

### Methods Implemented
1. **Normal Distribution Based**
   - Dependent and Independent covariance matrices
   - Maximum likelihood estimation

2. **GMM**
   - EM Algorithm implementation
   - Multiple Gaussian components
   - Log-likelihood optimization

3. **Parzen Window**
   - Two window sizes (h1=0.03, h2=0.5)
   - Non-parametric density estimation

4. **KNN**
   - Two K values (K1=5, K2=20)
   - Euclidean distance metric

5. **Linear Classifier**
   - Logistic regression
   - Gradient descent optimization
   - ROC curve analysis

## Multi-Class Classification

### Features
- 10-class classification problem
- Extended implementations of binary classifiers
- Comprehensive evaluation metrics

### Methods Implemented
1. **Normal Distribution**
2. **GMM**
   - Multiple Gaussian components per class
   - Log-likelihood plots
3. **Parzen Window**
   - Two window sizes
4. **KNN**
   - Both Euclidean and Cosine distance metrics
   - Two K values (K1=20, K2=50)
5. **Linear Classification**
   - One-vs-all approach
   - ROC curves for each class

## Requirements
- NumPy
- Matplotlib
- Python 3.x

## Usage
```python
# Example usage for binary classification
python binary_classification.py

# Example usage for multi-class classification
python multi_class_classification.py
```

## Results
- Confusion matrices
- ROC curves
- Accuracy metrics
- F1-scores

## License
MIT License
