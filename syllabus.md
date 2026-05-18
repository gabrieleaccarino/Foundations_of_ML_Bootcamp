# ML and Neural Networks for Climate Science

LEAP Summer Momentum Fellowship Bootcamp 2026 — *Two 90-minute lectures*

---

## Motivation

Extracting actionable knowledge from Earth system data requires methods capable of capturing complex, spatio-temporal, and highly non-linear dynamics across a wide range of scales. Machine learning (ML), and neural networks in particular, have emerged as transformative tools in Earth System science, enabling applications ranging from weather and climate emulation to extreme event prediction, data-driven forecasting, and surrogate modeling of subgrid-scale processes in numerical simulations.

This two-day lecture provides the foundational knowledge needed to design, implement, and train neural networks for Earth System science applications. Day 1 introduces the core principles of ML through examples based on linear and logistic regression. The goal is to build intuition using simple algorithms while establishing key concepts such as cost functions, gradient descent, and the bias–variance tradeoff, which naturally extend to more advanced architectures. The day concludes with an introduction to PyTorch, a widely used framework for developing and training ML models.

Day 2 extends these ideas to more advanced neural network architectures designed to capture complex non-linear relationships as well as spatial and temporal patterns in data. These include feed-forward neural networks, convolutional neural networks (CNNs), recurrent neural networks (RNNs), and long short-term memory (LSTM) networks. The sequence concludes with a hands-on session focused on the practical implementation, training, and evaluation of neural networks for Earth System science applications.

---

## Overview

### Day 1 — Introduction to ML and Neural Networks *(90 min)*

1. **ML fundamentals** — Definitions, types of ML and common pitfalls
2. **Regression and classification** — Linear regression, cost function, gradient descent, stochastic and mini-batch gradient descent, bias-variance tradeoff. Polynomial regression, Logistic regression, sigmoid, cross-entropy loss, and evaluation metrics (accuracy, precision, recall, F1, ROC-AUC).
3. **PyTorch and PyTorch Lightning** — Tensors, autograd, Dataset/DataLoader, building and training a neural network in PyTorch. PyTorch Lightning: LightningModule, Trainer, callbacks, mixed precision, multi-device training, and distribution strategies.

### Day 2 — Advanced Neural Network Architectures *(90 min)*

1. **Artificial neural networks** — Perceptron, feedforward architecture, activation functions and the role of non-linearity, cost functions, forward pass, backpropagation and the chain rule. Optimizers, mini-batch training.
2. **Convolutional neural networks** — Why fully connected networks are inefficient for images. The convolution operation: kernels, receptive fields, stride, padding. Multi-channel and 3D convolutions for spatiotemporal data. Pooling, full CNN architecture.
3. **Recurrent neural networks** — Why sequential data requires specialized architectures. RNN core formulation, architecture variants, backpropagation through time, and the vanishing/exploding gradient problem.
3. **Long Short-Term Memory networks** — Cell state as a gradient highway. The forget, input, and output gates. Why gating mitigates the vanishing gradient problem.

---

## Learning Objectives

By the end of these two lectures, students will be able to:

- distinguish between types of ML and identify which is appropriate for a given climate problem,
- formulate a supervised learning task with an appropriate cost function and evaluation metric,
- explain how neural networks learn through forward propagation, backpropagation, and gradient descent,
- describe how convolutional layers exploit spatial structure and why they are preferred for image-like climate data,
- explain the vanishing gradient problem and how LSTM gating mechanisms address it
- implement and train a neural network using PyTorch and PyTorch Lightning,

---

## Prerequisites

- Basic linear algebra (vectors, matrices, dot products)
- Python programming (NumPy familiarity helpful)
- No prior knowledge of ML or neural networks assumed

---

## References and Further Reading

### Textbooks
- Goodfellow, I., Bengio, Y. & Courville, A. (2016). *Deep Learning*. MIT Press. [deeplearningbook.org](https://www.deeplearningbook.org)
- Mitchell, T. (1997). *ML*. McGraw Hill.

### Tools and Documentation
- PyTorch: [pytorch.org/docs](https://pytorch.org/docs)
- PyTorch Lightning: [lightning.ai/docs/pytorch/stable](https://lightning.ai/docs/pytorch/stable/)
