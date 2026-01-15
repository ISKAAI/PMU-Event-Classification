# PMU Event Classification with RNN

## Overview
Time-series classification of PMU data from IEEE 39-bus system using a 2-layer RNN.

## Dataset
Bus39 Competition PMU dataset (14 features, 6 event classes).

## Method
- Sliding window (sequence length = 10)
- 2-layer Vanilla RNN (hidden size = 32)
- Dropout + L2 regularization
- Cross-entropy loss, Adam optimizer

## Results
- Test accuracy: 99.78%
- Confusion matrix and F1-score analysis

## Requirements
- Python 3
- pandas
- numpy
- scikit-learn
- PyTorch
- matplotlib
- seaborn
