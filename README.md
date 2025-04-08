# README: Gradient Descent Explained and Visualized

This repository contains a Jupyter Notebook (`Gradient_descent.ipynb`) that explains and demonstrates the Gradient Descent optimization algorithm.

## Overview

The notebook covers:

1.  **Conceptual Explanation:**
    *   Introduces Gradient Descent as an iterative optimization algorithm used to find the minimum of a function.
    *   Explains the role of the derivative (gradient) in determining the direction of descent and the learning rate in controlling the step size.
    *   Discusses the importance of choosing an appropriate learning rate.
    *   Briefly mentions adaptive optimizers (like Adam, RMSprop).

2.  **Python Implementation and Animation:**
    *   Provides Python code implementing Gradient Descent for a simple quadratic function (`f(x) = 3x^2 + 4x + 5`).
    *   Includes an animated visualization using `matplotlib` showing the steps taken by the algorithm as it converges towards the function's minimum.

3.  **Application in Neural Networks:**
    *   Explains how Gradient Descent is fundamentally used in training neural networks.
    *   Demonstrates how to calculate the gradients of a loss function (using Mean Squared Error - MSE as an example) with respect to the parameters (weights `w` and bias `b`) of a simple linear neuron.
    *   Shows the parameter update rules using the calculated gradients and a learning rate.

## How to Use

1.  Ensure you have Python and the necessary libraries installed (`numpy`, `matplotlib`). You might also need `ipympl` for the interactive widget backend in Jupyter:
    ```bash
    pip install numpy matplotlib ipympl jupyterlab # or jupyter notebook
    ```
2.  Clone or download this repository.
3.  Navigate to the directory containing the notebook in your terminal.
4.  Launch Jupyter Lab or Jupyter Notebook:
    ```bash
    jupyter lab
    # or
    jupyter notebook
    ```
5.  Open the `Gradient_descent.ipynb` file.
6.  Run the cells sequentially to read the explanations and view the animated demonstration.