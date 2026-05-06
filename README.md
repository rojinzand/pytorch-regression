# PyTorch Regression Project (y = x²)

## Overview
This project demonstrates a simple neural network built using PyTorch to learn and approximate the nonlinear function:

y = x²

The goal is to understand the basic workflow of training a neural network, including forward pass, loss computation, backpropagation, and optimization.

---

## Model Architecture
- Input layer: 1 neuron
- Hidden layers: 20 → 20 neurons
- Activation function: ReLU
- Output layer: 1 neuron

---

## Technologies Used
- Python
- PyTorch
- Matplotlib

---

## Training Process
- Loss function: Mean Squared Error (MSE)
- Optimizer: Adam (or SGD depending on implementation)
- Training loop includes forward pass, loss calculation, backward pass, and parameter updates.

---

## Results
The model successfully learns to approximate the function y = x².

The training loss decreases over epochs, and predictions closely follow the true function.

---

## How to Run
```bash
python regression.py

---

## What I Learned
- Building neural networks in PyTorch  
- Writing a training loop (forward pass, loss, backward pass, optimizer step)  
- Understanding regression problems  
- Visualizing results using Matplotlib  
- Basic idea of overfitting and generalization
