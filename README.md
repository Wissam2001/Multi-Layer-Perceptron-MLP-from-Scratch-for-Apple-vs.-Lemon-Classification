# Overview 📌
This project was developed as part of the Deep Learning Master's Lab assignment to implement a Multi-Layer Perceptron (MLP) from scratch using only NumPy and core Python libraries. The goal is to classify images of apples and lemons using a neural network built without high-level deep learning frameworks like TensorFlow or Keras.

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

  # Dataset 🗂️
  **Classes:** Apple (0), Lemon (1)
  **Data split:**
  - Training: 200 images (100 apples + 100 lemons)
  - Testing: 100 images (50 apples + 50 lemons)
  **Image size:** 64×64 pixels (after resizing)
  **Format:** PNG images loaded using OpenCV
    The dataset is available at the following link

     https://drive.google.com/file/d/1ZtVTTxAHMavnYdeCUoqQyaZkNk_eF3IR/view?usp=shari ng

  # Libraries 📚
  - **NumPy:** Matrix operations and neural network implementation
  - **OpenCV:** Image loading and preprocessing
  - **Matplotlib** Loss curves visualization
  - **Scikit-learn:** Confusion matrix and classification report

  # Lessons Learned 🧠
  - **Activation function choice is critical:** Sigmoid is suitable for binary classification outputs, while ReLU may fail if used in the output layer.
  - **Weight initialization matters:** Random initialization breaks symmetry; zero initialization prevents learning entirely.
  - **Gradient descent variants affect convergence speed and stability:**
    * BGD: stable but slow
    * SGD: faster but noisy
    * MGD: balanced trade-off
   - **Implementing backpropagation manually provides deep insight into how neural networks learn.**
 
  # License 📝
  This project is for educational purposes as part of a Master's lab assignment.

  # Contact ✉️
  • **Email:** wissambadia4@gmail.com
  • **LinkedIn:** [Badia Ouissam Lakas](linkedin.com/in/badia-ouissam-lakas-a66a28214)  
