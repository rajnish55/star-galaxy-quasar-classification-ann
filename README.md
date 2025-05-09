# Star, Galaxy, and Quasar Classification using ANN

This project implements a multi-class classification of astronomical objects (stars, galaxies, and quasars) using Artificial Neural Networks (ANNs). The dataset used in this project is sourced from [Kaggle's Stellar Classification Dataset (SDSS17)](https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17), which contains photometric data for various astronomical objects.

## Overview

The goal of this project is to classify astronomical objects into three categories:
- **Stars**
- **Galaxies**
- **Quasars**

We utilize an Artificial Neural Network (ANN) for this classification task. The project is organized into the following stages:
1. Data preprocessing
2. Model design and architecture
3. Training and evaluation
4. Prediction and performance metrics

## Dataset

The dataset used in this project is provided by the Sloan Digital Sky Survey (SDSS) and consists of photometric data. It includes features such as:
- Magnitudes in different photometric bands
- Redshift values
- Other observational features

You can download the dataset from [Kaggle here](https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17).

### Dataset Features:
- **class**: The target variable (Star, Galaxy, Quasar).
- **u, g, r, i, z**: Magnitudes in the SDSS photometric bands.
- **redshift**: The redshift of the object.
- **other columns**: Additional observational features.

