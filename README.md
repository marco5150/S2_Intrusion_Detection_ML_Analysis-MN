**Intrusion Detection Using Machine Learning (Random Forest vs Neural Network):
**
This repository contains the implementation for the project "Intrusion Detection Machine Learning Analysis", authored by Marco Naumov as part of an assignment for my AI module.

The study evaluates whether supervised machine learning algorithms can accurately detect malicious network traffic using the NSL-KDD benchmark dataset.

The project compares two classification models:
Random Forest Classifier
Multi-Layer Perceptron (Neural Network)
A full research report accompanies this repository.

Project Overview:
This project investigates the following research question:

**Can machine learning accurately detect malicious network traffic using supervised classification algorithms?**

To answer this, two machine learning models were trained and evaluated on the NSL-KDD dataset using:
Accuracy
Precision
Recall
F1-score
ROC-AUC
Confusion Matrices
Training Time
The results provide a comparative analysis of model behaviour, performance trade-offs, and suitability for intrusion detection systems (IDS).

Key Findings:
The Neural Network (MLP) achieved higher recall and F1-score, making it more effective at detecting a wider range of attacks.
The Random Forest showed higher precision and faster training time, but lower recall, meaning it missed more attacks.
ROC analysis demonstrated stronger theoretical separability for the Random Forest, but neural networks provided better balanced detection.
These trade-offs emphasise the importance of metric selection, dataset balance, and operational context when developing IDS solutions.

Full analysis is available in the accompanying paper.

This project uses the NSL-KDD dataset, which can be downloaded from: https://www.kaggle.com/datasets/hassan06/nslkdd/data
