# Kannada Digit Recognition

This project builds and evaluates a Kannada digit recognition model using image-based features and machine learning classifiers.

## What is included
- A Jupyter notebook for data loading, preprocessing, training, evaluation, and prediction
- A simple custom-image prediction workflow
- Dependencies listed in requirements.txt

## Dataset
The notebook expects the Kannada MNIST-style datasets:
- train.csv
- Dig-MNIST.csv
- test.csv
- kannada-mnsit.zip

## Setup
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Open the notebook and run the cells in order.

## Project workflow
- Load and inspect the dataset
- Extract HOG features
- Train multiple classifiers
- Evaluate accuracy and F1 score
- Generate predictions for the test set
- Predict custom uploaded digits

## Notes
The notebook uses OpenCV, scikit-image, scikit-learn, pandas, and matplotlib.
