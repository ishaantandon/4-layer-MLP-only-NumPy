## 4-Layer MLP from Scratch (NumPy only)

Built a fully connected neural network from scratch using only NumPy 
to deeply understand backpropagation and gradient flow. 
No PyTorch, no TensorFlow.

Architecture: 784 → 48 → 48 → 10
Dataset: MNIST
Optimizer: Batch Gradient Descent (α = 0.1, α = 0.95*α )
Final Accuracy: ~91% (training), 500 iterations
