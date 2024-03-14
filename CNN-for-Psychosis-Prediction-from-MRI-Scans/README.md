# Predicting Psychosis with CNNs on Brain MRIs

## Introduction
This project aims to use Convolutional Neural Networks (CNNs) to predict psychosis from brain MRI scans. The study compares three different CNN architectures: a deep plain neural network, ResNet, and a wide and deep model, to evaluate their effectiveness in a binary classification task.

# Project Structure

This project includes various files and directories which are organized as follows:

- `PIPELINE.png`
  - This file contains the training and evaluation pipeline.

- `non_sequential_wide_and_deep_architecture.png`
  - The non-sequential wide and deep neural network architecture used in the project.

- `notebook.html`
  - An exported version of a Jupyter Notebook containing the code, outputs, and documentation of the analyses conducted. please download to view it.

- `report.pdf`
  - The detailed report of the project, including methodology, results, and conclusions.

- `roc_curve.png`
  - Receiver Operating Characteristic (ROC) curve graph for models being experimented with.

- `sequential_deep_neural_network.png`
  - The architecture of a sequential deep neural network model used within the project.

## Dataset
The dataset comprises MRI scans from individuals diagnosed with first-episode psychosis (FEP) and healthy controls (HC), with a total of 674 records. We are not sharing the dataset for privacy and security reasons.

## Models Overview
Three models were compared in this study:
- **Sequential Deep Neural Network**: A basic CNN with layers optimized to prevent overfitting due to a smaller dataset size.
- **Non-Sequential Wide and Deep Model**: Inspired by architectures used for recommender systems, this model uses wide architecture to learn general patterns and deep networks for more complex ones.
- **Residual Network (ResNet)**: A simplified version of ResNet with fewer layers to accommodate for limited computational resources.

The non-sequential wide and deep model outperformed the other two, achieving an 88% training accuracy and 60.4% test accuracy with a 63% error rate.

## Authors:
1. Ameer Sohail Syed
2. Chandni.
3. Zoya.
4. Subhalakshmi

## How to Contribute

Feel free to contribute to this project by providing suggestions, improvements, or by extending the research with your own experiments and findings.
