# BrainerX AI & Data Science Coursework

A collection of hands-on notebooks completed while studying data science, machine learning and deep learning.

## Featured deep-learning project

### Cats vs. Dogs — Transfer Learning & Fine-Tuning Benchmark

A complete computer-vision benchmark comparing five ImageNet-pretrained CNN backbones:

- VGG16
- ResNet50
- InceptionV3
- MobileNetV2
- EfficientNetB0

The notebook now uses a consistent two-stage workflow for every architecture:

1. train a compact classifier head with the pretrained backbone frozen;
2. fine-tune the trained checkpoint by selectively unfreezing the final backbone layers.

It also includes:

- architecture-specific preprocessing
- data augmentation
- GlobalAveragePooling2D classifier heads
- dropout
- early stopping
- learning-rate reduction
- frozen BatchNormalization layers during fine-tuning
- accuracy, precision, recall and ROC-AUC
- classification reports
- confusion matrices
- trainable-parameter and training-time comparison

**Notebook:** [transfer_learning.ipynb](./transfer_learning.ipynb)

**Open in Colab:** https://colab.research.google.com/github/XenosPro/BrainerX_homeworks/blob/main/transfer_learning.ipynb

> Final benchmark numbers should be taken from a fresh top-to-bottom GPU run so every result comes from the same execution.

## Other coursework

### Atlas HR Consulting — Salary Benchmarking

Exploratory data analysis focused on cleaning, distributions, correlations and interpretation of HR salary data.

### PulseFit — Weekly Calorie Estimator

Regression project covering exploratory analysis, preprocessing, feature preparation, model training and evaluation.

## Portfolio

https://xenospro.github.io/Portfolio/
