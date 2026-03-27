 #Semi-Supervised Learning Tutorial: Self-Training on Breast Cancer Dataset

## Overview
This project demonstrates how semi-supervised learning can improve classification performance when labelled data is limited. It compares supervised learning with a self-training approach using the Breast Cancer Wisconsin dataset.

## Objectives
- Understand supervised vs semi-supervised learning
- Apply self-training using labelled and unlabelled data
- Compare model performance across different label percentages

## Dataset
Breast Cancer Wisconsin (Diagnostic)
- 569 samples
- 30 features
- Binary classification (benign vs malignant)

Link:
https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)

## Methodology
1. Split data into train/test
2. Simulate limited labels (100%, 50%, 20%, 10%)
3. Train supervised model (Random Forest)
4. Train semi-supervised model (Self-Training)
5. Evaluate using accuracy, confusion matrix, ROC curve

## Key Results
- Semi-supervised learning improves performance when labels are limited
- Largest improvements seen at 20% and 10% labels
- Performance gap increases as labelled data decreases

## Limitations
- Error propagation from incorrect pseudo-labels
- Requires careful threshold tuning

## Applications
- Medical diagnosis
- Fraud detection
- NLP and text classification

## How to Run
1. Install required libraries: numpy, pandas, matplotlib, scikit-learn
2. Run the notebook or script
3. Review outputs and visualisations


