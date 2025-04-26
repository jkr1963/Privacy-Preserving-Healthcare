Secure Federated Analytics for Privacy (SFAP)
Project Overview

This project demonstrates privacy-preserving healthcare analytics using Federated Learning (FL) and Differential Privacy (DP). We simulate two hospitals training a shared model for diabetes prediction using the Indian Diabetes Dataset, without exchanging raw patient data. Privacy is enhanced by adding noise during training using Opacus.

Key Features

Federated Learning: Local training on split datasets representing different hospitals.
Differential Privacy: Gradient noise injection to protect sensitive data.
Federated Averaging: Combine model updates from multiple clients.
Comparison: Accuracy trends of normal FL vs FL + DP.
Visualization: Graphs showing accuracy over federated rounds.

Dataset

Name: PIMA Indian Diabetes Dataset
Source: [Kaggle Link](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
Details: 8 input features (e.g., glucose, BMI, age) and 1 output (diabetes: 0 or 1).
