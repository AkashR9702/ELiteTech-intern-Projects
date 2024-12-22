# Iris Flower Classification

This project demonstrates the classification of iris flowers into three species — Setosa, Versicolor, and Virginica — based on their physical measurements (sepal length, sepal width, petal length, petal width). It utilizes a **Random Forest Classifier** from Scikit-learn and achieves high accuracy on the dataset.

---

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

---

## Overview

The Iris dataset is a classic dataset in machine learning, containing 150 samples with 4 features each. This project:
- Performs exploratory data analysis (EDA).
- Trains a Random Forest model to classify the flowers.
- Evaluates the model using metrics like accuracy, precision, recall, and confusion matrix.

---

## Dataset

- **Source**: The dataset is included in Scikit-learn (`sklearn.datasets.load_iris`).
- **Features**: Sepal length, sepal width, petal length, and petal width.
- **Target**: Species (Setosa, Versicolor, Virginica).



---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/AkashR9702/Iris-Flower-Classification.git


2. Navigate the project folder

   cd Iris-Flower-Classification

3.install dependencies(if ur using virtual env)

  pip install -r requirement.txt



##Usage

Open the Jupyter Notebook:

jupyter notebook IRIS_CLASSIFICATION.ipynb

Run the cells step-by-step to:
1.Load and explore the dataset.
2.Train and evaluate the model.
3.Visualize results.


##Results
Accuracy: 100% on the test set.

Cross-Validation Score: ~99.33% (mean of 5 folds).

Visualizations include:
1.Pairplot of features by species.
2.Confusion matrix heatmap.
3.Decision boundaries for petal length and petal width.

