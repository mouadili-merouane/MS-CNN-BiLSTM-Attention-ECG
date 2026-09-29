# ECG Arrhythmia Classification Using Deep Learning

## Overview

This repository contains the Python notebook used for ECG heartbeat classification based on the MIT-BIH Arrhythmia Database.

The notebook covers data preparation, model training, evaluation, ablation experiments, and statistical analysis. It includes the following models:

- Random Forest
- XGBoost
- CNN Baseline
- CNN-LSTM
- MS-CNN-BiLSTM-Attention

It also includes ablation experiments to study the contribution of individual components:
- Without BiLSTM
- Without Attention
- Without Multi-Scale CNN (MCNN)

## Requirements

The experiments were developed using Python and Jupyter Notebook (or Google Colab).

Install the required libraries:

```python
!pip install wfdb -q
!pip install numpy pandas matplotlib seaborn scikit-learn tensorflow scipy

The dataset is available from PhysioNet
