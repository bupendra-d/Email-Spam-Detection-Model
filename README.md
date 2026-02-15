## Email Spam Detection Model:
This project implements an email spam detection system using machine learning and natural language processing techniques.

## Overview:
- Text preprocessing using **TF-IDF Vectorization**
- Model comparison using:
  - Logistic Regression
  - Multinomial Naive Bayes
  - Linear Support Vector Machine (SVM)
- Final model selection based on cross-validation performance
- End-to-end pipeline for training and inference

## Final Model
- **Linear SVM (LinearSVC)**
- Selected due to highest cross-validation accuracy and strong performance on high-dimensional text data

## How to Run
```bash
pip install -r requirements.txt
python model_building.py
