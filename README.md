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

  # Dataset 🗂️
  **Classes:** Apple (0), Lemon (1)
  **Data split:**
  - Training: 200 images (100 apples + 100 lemons)
  - Testing: 100 images (50 apples + 50 lemons)
  **Image size:** 64×64 pixels (after resizing)
  **Format:** PNG images loaded using OpenCV
    The dataset is available in the following link

     https://drive.google.com/file/d/1ZtVTTxAHMavnYdeCUoqQyaZkNk_eF3IR/view?usp=shari ng   
- Visualize training progress using loss curves.
- Evaluate classification performance using confusion matrices.
