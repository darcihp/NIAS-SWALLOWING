# NIAS-SWALLOWING-V1

Dataset and initial pipeline for clinical image classification related to the NIAS-SWALLOWING-V1 project.

## Dataset Structure

The dataset is organized as follows:

```text
dataset_augmented/
│
├── train/
│   ├── A/
│   └── N/
│
├── val/
│   ├── A/
│   └── N/
│
└── test/
    ├── A/
    └── N/
```

## Classes

- `A` → Class A
- `N` → Class N

## Dataset Split

The dataset was divided using stratified splitting:

- 70% training
- 15% validation
- 15% testing

The split files are available in:

```text
splits/
├── train_split.csv
├── val_split.csv
└── test_split.csv
```

## Data Augmentation

Training images received data augmentation techniques, including:

- Horizontal flip
- Small rotations
- Zoom
- Contrast adjustment

Validation and test images remained unchanged to ensure realistic model evaluation.

## Objective

This repository will be used for training and evaluation of Deep Learning models applied to clinical image classification using Transfer Learning techniques.

## Technologies Used

- Python
- TensorFlow / Keras
- Google Colab
- Scikit-learn

## Expected Results

The experiments include generation of:

- Confusion Matrix
- Accuracy
- Recall
- Precision
- F1-Score
- ROC Curve / AUC

## Notes

This project is currently under early development.

