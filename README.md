# Anomaly Detection in Medical Devices and Aerospace Systems Using Generative Models

## Project Description

This project aims to evaluate and apply various generative machine learning models for anomaly detection in medical devices and aerospace systems. The focus is on leveraging models like Hidden Markov Models (HMM), Variational Autoencoders (VAE), and Generative Adversarial Networks (GAN) to identify faults or anomalies in sensor readings. The models are benchmarked based on metrics like accuracy, precision, and recall.

## Table of Contents

- [Datasets](#datasets)
- [Methodology](#methodology)
- [Evaluation Metrics](#evaluation-metrics)
- [Jupyter Notebooks](#jupyter-notebooks)
- [Acknowledgments](#acknowledgments)

## Datasets

Two datasets are used for this project:

1. **Airbus Helicopter Accelerometer Dataset**: This dataset contains sensor readings related to an Airbus Helicopter system. The dataset is publicly available and can be accessed from [ETH Zürich's Research Collection](https://www.research-collection.ethz.ch/handle/20.500.11850/415151).
    - Notebooks: `HMM_Airbus.ipynb`, `GAN Airbus.ipynb`, `VAE_Airbus.ipynb`

2. **Surgical Stapler Dataset**: This dataset is provided by Medtronic's surgical operating unit and contains lab experiment readings from surgical staplers.
    - Notebooks: `HMM_Stapler.ipynb`, `GAN_Stapler.ipynb`, `VAE_Stapler.ipynb`

> **Note**: The data from the medical device was obtained from a lab experiment and not from a clinical setting. Real values are anonymized for protection.

## Methodology

The project employs a series of data pre-processing, training, and evaluation steps, each tailored to the specific requirements of the dataset and the model in use. For a detailed methodology, please refer to the Jupyter notebooks in the repository.

## Evaluation Metrics

The models are evaluated based on the following metrics:

- Accuracy
- Precision
- Recall

## Jupyter Notebooks

- `HMM_Airbus.ipynb`: HMM model for Airbus dataset
- `GAN Airbus.ipynb`: GAN model for Airbus dataset
- `VAE_Airbus.ipynb`: VAE model for Airbus dataset
- `HMM_Stapler.ipynb`: HMM model for Surgical Stapler dataset
- `GAN_Stapler.ipynb`: GAN model for Surgical Stapler dataset
- `VAE_Stapler.ipynb`: VAE model for Surgical Stapler dataset

## Acknowledgments

Special thanks to Medtronic's surgical operating unit for providing access to the Surgical Stapler dataset. The dataset was collected during lab experiments and is not clinical data. All real values have been anonymized for protection.

