# Capstone_Experiments_DeepLearning
Deep Learning Experiments using TensorFlow & Keras

This repository contains three practical deep learning experiments implemented using Feedforward Neural Networks (FNN), Convolutional Neural Networks (CNN), and Long Short-Term Memory Networks (LSTM).

The goal is to demonstrate how different neural network architectures solve different types of machine learning problems:

Tabular classification
Image classification
Time-series prediction
Repository Structure
Capstone_Experiments_DeepLearning/
│
├── Experiment_1.ipynb   # FNN – Breast Cancer Classification
├── Experiment_2.ipynb   # CNN – Fashion MNIST Classification
├── Experiment_3.ipynb   # LSTM – Time Series Prediction
└── README.md

---

# Experiment 1: Feedforward Neural Network (FNN)
Objective

Classify tumors as malignant or benign using a dense neural network.

Dataset

Breast Cancer Dataset (from Scikit-learn)

Feature	Value
Samples	569
Features	30
Type	Binary Classification
Workflow
Load dataset
Normalize features
Split into train/test sets
Build dense neural network
Apply dropout regularization
Train model
Evaluate performance
Model Architecture
Input Layer
Dense Layer (ReLU)
Dropout
Dense Output Layer (Sigmoid)
Output
Accuracy vs Epoch graph
Loss vs Epoch graph
Classification performance evaluation

---

# Experiment 2: Convolutional Neural Network (CNN)
Objective

Classify grayscale fashion images into 10 clothing categories using CNN.

Dataset

Fashion-MNIST Dataset

Training Images	Testing Images	Classes
60,000	10,000	10

Examples include:

T-shirts
Shirts
Sneakers
Bags
Dresses
Workflow
Normalize image pixels
Reshape dataset
Build CNN architecture
Apply MaxPooling
Add Dropout
Train model
Evaluate accuracy
Model Architecture
Conv2D
MaxPooling2D
Conv2D
MaxPooling2D
Flatten
Dense
Dropout
Softmax Output Layer
Output
Training accuracy graph
Validation accuracy graph
Loss vs Epoch graph

---

# Experiment 3: LSTM for Time-Series Prediction
Objective

Predict sequential values from sine wave data using LSTM networks.

Dataset

Synthetic sine wave time-series dataset

Used to demonstrate sequence learning capability.

Workflow
Generate sine wave dataset
Create input sequences
Train/test split
Build LSTM network
Apply EarlyStopping
Predict sequence values
Compare predictions with actual values
Model Architecture
LSTM Layer
Dropout Layer
Dense Output Layer
Output
Predicted vs actual signal plot
Training loss visualization
Technologies Used
Tool	Purpose
Python	Programming language
TensorFlow / Keras	Deep learning framework
NumPy	Numerical operations
Matplotlib	Visualization
Scikit-learn	Dataset + preprocessing
Installation

---

Install dependencies before running notebooks:

pip install tensorflow numpy matplotlib scikit-learn
How to Run

Launch Jupyter Notebook:

jupyter notebook

Run experiments in order:

Experiment_1.ipynb
Experiment_2.ipynb
Experiment_3.ipynb

Execute cells sequentially.

Learning Outcomes

After completing these experiments, you will understand:

How FNN handles structured datasets
How CNN extracts spatial image features
How LSTM models sequential data
Model training workflow in TensorFlow/Keras
Performance evaluation using accuracy and loss curves
Future Improvements

Possible extensions:

Add model evaluation metrics (Precision, Recall, F1-score)
Add a confusion matrix visualization
Train a CNN with data augmentation
Apply LSTM on real-world datasets

---

# Author

**Vishakha Gaur** - **2501940065*

---
