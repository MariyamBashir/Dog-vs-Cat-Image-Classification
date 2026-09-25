# Dog vs. Cat Image Classification

A Computer Vision project that classifies images as either a dog or a cat, comparing deep learning and classical machine learning approaches.

## Dataset
Kaggle's Dogs vs. Cats dataset.

## Approach
- **Primary model:** ResNeXt50 (pretrained CNN backbone) + Logistic Regression classifier on extracted features
- **Alternative model:** Support Vector Machine (SVM), used as a comparison baseline against the CNN-based approach

## Results
- ResNeXt50 + Logistic Regression accuracy: _add your %_
- SVM accuracy: _add your %_

## Tech Stack
Python, PyTorch/TensorFlow (whichever you used), scikit-learn, Kaggle dataset

## Notebook
See `cats-and-dogs-vs-logistic-regression.ipynb` in this repo for the full implementation.
