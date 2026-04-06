# Overview 📌
This project was developed as part of a Master's Lab assignment to implement a Multi-Layer Perceptron (MLP) from scratch using only NumPy and core Python libraries. The goal is to classify images of apples and lemons using a neural network built without high-level deep learning frameworks like TensorFlow or Keras.

The project explores the fundamental concepts of neural networks, including forward propagation, backpropagation, gradient descent variants, activation functions, and weight initialization strategies.

# Features ✨
- Fully custom MLP implementation (no deep learning libraries used)
- Two activation functions: ReLU and Sigmoid
- Three gradient descent methods:
  * Batch Gradient Descent (BGD)
  * Mini-Batch Gradient Descent (MGD)
  * Stochastic Gradient Descent (SGD)
- Weight initialization options:
  * Random (normal distribution)
  * Zero initialization (for comparative analysis)
- Mean Squared Error (MSE) as the loss function
- Preprocessing pipeline:
  * Grayscale conversion
  * Image resizing to 64×64
  * Min-Max normalization (scaling by 255)
  * Flattening to 1D vectors (4096 features)
- Evaluation metrics:
  * Confusion Matrix
  * Loss curves over epochs
 
  # Project Objectives 🎯
The primary objectives of this lab project were to:
- Understand the inner workings of an MLP by implementing it from scratch.
- Compare optimization algorithms (SGD, BGD, MGD) in terms of loss convergence and training time.
- Analyze the effect of activation functions (ReLU vs. Sigmoid) on learning and performance.
- Investigate weight initialization (random vs. zero) and its impact on the network's ability to learn.
- Visualize training progress using loss curves.
- Evaluate classification performance using confusion matrices.
