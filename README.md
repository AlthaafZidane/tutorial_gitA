# Tutorial Modeling Data Health Insurance

Tutorial ini akan mengolah data Health Insurance menjadi data yang siap untuk dilakukan pemodelan.

## Prerequisites

1. Download Data [here](https://www.kaggle.com/datasets/anmolkumar/health-insurance-cross-sell-prediction)
2. Instalasi dengan `pip install requirements.txt`

## Getting Started

- Dataset Splitting
- Training
- Model Validation

### Dataset Splitting

Split data into training, validation and test sets
```code
x_train, y_train, x_test, y_test = dataset_splitting()
```