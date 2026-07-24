# Multi-Layer Perceptron (MLP): Solving the XOR Problem

## Overview
Building on the limitations of single-layer perceptrons, this repository implements a Multi-Layer Perceptron (MLP) to successfully solve non-linear binary classification tasks. 

Using a practical scenario—predicting whether a person will go out to play basketball based on time and weather—the dataset mirrors the classic **XOR logic gate**. This project demonstrates how introducing hidden layers allows neural networks to learn complex, non-linear patterns that early linear classifiers could not handle.

## Key Takeaways
* **Overcoming Linear Limitations:** Unlike the single-layer perceptron, which completely fails at the XOR problem, this MLP model achieves **100% accuracy** on the exact same dataset.
* **Visualising Hidden Layers:** The decision boundary visualisation clearly shows the model capturing the non-linear relationship. Instead of a single straight line, the MLP carves out a specific region to accurately separate the classes.
* **Framework Implementation:** Transitioned from a raw math implementation to utilising `scikit-learn`'s `MLPClassifier`, leveraging the `lbfgs` solver and logistic activation functions for efficient training.

## Technologies Used
* **Python**
* **Scikit-Learn (sklearn):** Used to build, train, and evaluate the `MLPClassifier`.
* **NumPy:** For data preparation and grid generation.
* **Pandas:** For structuring and displaying the truth table predictions.
* **Matplotlib:** For visualising the non-linear decision boundary.

## How to Run
Open the Jupyter Notebook (`Layers_in_Neural_Network.ipynb`) and execute the cells sequentially. The notebook is broken down into clear steps: preparing the dataset, building the model, training, evaluating accuracy, and finally generating the decision boundary plot.
