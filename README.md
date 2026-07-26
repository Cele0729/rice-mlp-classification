# rice-mlp-classification
# Rice Variety Classification using a Multilayer Perceptron (MLP)

## Overview

This project implements a Multilayer Perceptron (MLP) neural network capable of classifying five rice varieties using morphological characteristics extracted from the Rice MSC Dataset.

The project was developed as part of the Advanced Artificial Intelligence course in Software Engineering.

## Dataset

- Source: Rice MSC Dataset (Kaggle)
- Samples: 75,000
- Features: 106
- Classes:
  - Arborio
  - Basmati
  - Ipsala
  - Jasmine
  - Karacadag

## Technologies

- Python
- Google Colab
- TensorFlow / Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Model Architecture

- Input Layer: 106 features
- Hidden Layer 1: 128 neurons (ReLU)
- Hidden Layer 2: 64 neurons (ReLU)
- Output Layer: 5 neurons (Softmax)

## Results

- Training Accuracy: ~99.94%
- Validation Accuracy: ~99.88%
- Test Accuracy: ~99%

The model demonstrated excellent performance in classifying rice varieties.

## Repository Structure

```text
images/
dataset/
IA_Clasificacion_Arroz_MLP.ipynb
informe.pdf
README.md
requirements.txt
```

## Author

Johan David Celemin Barragán
Software Engineering Student
