# Feed Forward Neural Network  Zalando MNIST

## Introduction
Ensemble-based Fashion-MNIST classification using Feed-Forward Neural Networks.
Implementation of a 10-model ensemble approach for binary classification tasks, analyzing confidence metrics and
classification reliability on the Zalando Fashion-MNIST dataset.

## Project Overview
This project focuses on improving image classification using ensemble methods and confidence estimation on the
Fashion-MNIST dataset.

## Task Description
The goal is to develop and analyze an ensemble-based classification system using binary classifiers for Fashion-MNIST
images.

## Technical Requirements
- Dataset: Fashion-MNIST by Zalando
- Method: Feed-Forward Neural Network (FNN)
- Ensemble Size: 10 models
- Image Preprocessing: Grayscale conversion

## Implementation Steps
### Data Preparation
- Convert images to grayscale format
- Split dataset into training and test sets
- Create binary classification tasks (one class vs. rest)

### Model Development
- Train 10 separate FNN models
- Each model performs binary classification
- Models should be lightweight for computational efficiency

### Ensemble Processing
- Process each image through all 10 models
- Implement majority voting mechanism
- Use voting frequency as confidence measure

## Research Questions
1. What classification score can be achieved using the ensemble approach?
2. How are confidence measures distributed across training and test images?
3. What is the difference in confidence measures between correctly and incorrectly classified images?

## Expected Deliverables
- Implementation of the ensemble classification system
- Analysis of classification performance
- Distribution analysis of confidence measures
- Comparison of confidence measures for correct/incorrect classifications

## Technical Notes
- Keep models small and efficient
- Implement proper validation methods
- Focus on confidence metric analysis