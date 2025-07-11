# Grokking Deep Learning

This project contains Jupyter notebooks that explore foundational concepts in deep learning, focusing on neural networks and how they learn from data.

## Overview

The project consists of two main notebooks:

### 1. intro-neural.ipynb
This notebook introduces the basics of neural networks, including:
- What a neural network is and how it makes predictions
- The role of input data and weights in predictions
- Working with single and multiple inputs
- Vector math and elementwise operations essential for deep learning
- Making multiple outputs predictions
- Matrix multiplication for neural networks
- Stacked neural networks and the concept of forward propagation

### 2. com-learn.ipynb
This notebook covers how neural networks learn from their predictions by:
- Comparing predictions to actual values using Mean Squared Error (MSE)
- The "Hot and Cold" learning method for adjusting weights
- Using a learning rate to iteratively improve predictions
- Understanding the basics of gradient descent and error minimization

## How to Run

1. Ensure you have Python installed (preferably Python 3.10 or later).
2. It is recommended to use a virtual environment. You can create and activate one as follows:
   ```bash
   python3 -m venv myvenv
   source myvenv/bin/activate  # On Windows use `myvenv\Scripts\activate`
   ```
3. Install Jupyter Notebook if not already installed:
   ```bash
   pip install notebook numpy
   ```
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open and run the notebooks `intro-neural.ipynb` and `com-learn.ipynb` in the `grokking-deeplearning` directory.

## Key Concepts Learned

- Neural networks use weights to scale inputs and make predictions.
- Predictions can be improved by adjusting weights based on errors.
- Vector and matrix operations are fundamental to neural network computations.
- Learning involves comparing predictions to goals and adjusting weights to minimize error.
- The "Hot and Cold" method is a simple approach to learning by tweaking weights.
- Forward propagation is the process of passing inputs through layers to get predictions.

## Next Steps

- Explore more advanced learning algorithms like backpropagation.
- Experiment with deeper and more complex neural network architectures.
- Apply these concepts to real-world datasets and problems.

---

This README summarizes the progress made so far in understanding and implementing basic neural network concepts and learning mechanisms.
