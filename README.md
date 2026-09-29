# Hybrid Two-Stage Deep Learning-Based Network Intrusion Detection System

## About the Project

This project focuses on network intrusion detection using deep learning. It was developed as part of my master's dissertation and explores a two-stage approach to detecting suspicious network traffic and classifying cyberattacks.

The first stage uses an Autoencoder to detect anomalous traffic based on reconstruction error. The second stage uses a CNN-BiLSTM model with an attention mechanism to classify network traffic.

## Approach

**Stage 1 — Anomaly Detection**

* The Autoencoder is trained using benign network traffic.
* Reconstruction error is used to identify potentially anomalous traffic.
* A threshold is determined using benign validation samples.

**Stage 2 — Attack Classification**

* CNN layers are used to extract traffic feature patterns.
* BiLSTM layers capture relationships in the learned representations.
* An attention mechanism helps the model focus on relevant information.
* The model classifies traffic into different categories.

## Dataset

The experiments use the CIC-IDS2017 dataset, which contains benign network traffic and several types of network attacks.

Dataset: https://www.unb.ca/cic/datasets/ids-2017.html

The dataset files are not included in this repository.

## Tools and Libraries

* Python
* PyTorch
* Pandas and NumPy
* Scikit-learn
* Matplotlib and Seaborn
* Jupyter Notebook / Google Colab

## Evaluation

Model performance is assessed using accuracy, precision, recall, F1-score, and confusion matrices.

Experimental results and visualizations will be added to the repository as the project is organized.

## Repository Contents

* `notebooks/` — model development and experiments
* `src/` — source code
* `results/` — evaluation results and visualizations
* `requirements.txt` — project dependencies

## Author

Sariyya Aliyeva

Master's Dissertation Project — Data Analytics
