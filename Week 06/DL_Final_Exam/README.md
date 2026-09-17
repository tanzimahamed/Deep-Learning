# Deep Learning Final Exam — KMNIST Classification

This repository contains my Deep Learning Final Exam solution using a
Neural Network to classify KMNIST handwritten Japanese characters.

## 📌 Dataset

- Dataset: KMNIST
- Image Size: 28 × 28 grayscale
- Number of Classes: 10
- Classes: o, ki, su, tsu, na, ha, ma, ya, re, wo

## 🧠 Model Architecture

The model is a fully connected neural network:

28 × 28 → 784 → 512 → 256 → 128 → 10

Each hidden layer uses:

- Linear Layer
- Batch Normalization
- ReLU Activation

The output layer contains 10 neurons for 10-class classification.

## ⚙️ Training

- Loss Function: CrossEntropyLoss
- Optimizer: Adam
- Learning Rate: 0.001
- Epochs: 15
- Batch Size: 256
- Train/Validation Split: 50,000 / 10,000

## 📊 Evaluation

The model was evaluated using:

- Test Accuracy
- Training and Validation Loss Curve
- Confusion Matrix
- Classification Analysis

## 🛠️ Technologies Used

- Python
- PyTorch
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

## 📁 Repository Contents

- `DL_Final_Exam_Answer.ipynb` — Complete exam solution
- `README.md` — Project documentation

## 🎯 Learning Objectives

Through this work, I practiced:

- Dataset preprocessing
- Data normalization
- Train/validation splitting
- PyTorch TensorDataset and DataLoader
- Neural Network design
- Batch Normalization
- Model training and validation
- Test evaluation
- Confusion Matrix analysis

## 👨‍💻 Author

Tanzim Ahamed

Department of Information & Communication Engineering (ICE)

Daffodil International University

Phitron AI/ML Batch-2
