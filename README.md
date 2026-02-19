# XOR_MLP – PyTorch Lightning Implementation

A simple Multi-Layer Perceptron (MLP) built using PyTorch Lightning to solve the classic XOR problem.

🔗 **Open in Colab:** [Run Notebook](https://colab.research.google.com/drive/1MjAzCAIoE-tcfeiUO9Zh1rNfWLT7N1j-?usp=sharing)

---

## Model Architecture

- Input Layer: 2 neurons  
- Hidden Layer 1: 8 neurons + ReLU  
- Hidden Layer 2: 4 neurons + ReLU  
- Output Layer: 1 neuron + Sigmoid  
- Loss Function: Binary Cross Entropy (BCELoss)  
- Optimizer: Adam  

---

## 📌 Why XOR?

The XOR function is **not linearly separable**, meaning a single-layer perceptron cannot solve it.

By adding:
- Hidden layers  
- Non-linear activation functions (ReLU)  

The network learns a non-linear decision boundary.

---

## 🧪 Expected Predictions

| Input | Output |
|-------|--------|
| (0,0) | 0 |
| (0,1) | 1 |
| (1,0) | 1 |
| (1,1) | 0 |
