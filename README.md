# Simple Neural Network from Scratch

## Overview

This repository contains a Jupyter notebook where we build and explain a simple neural network **from scratch** using only basic Python. No external libraries like TensorFlow, PyTorch, or NumPy are used—just raw Python code to help beginners understand the fundamental concepts of neural networks.

### What's Inside?

- A complete explanation of **forward propagation** in neural networks.
- A simple **neural network model** with:
  - 2 neurons in the input layer.
  - 2 neurons in the hidden layer.
  - 1 neuron in the output layer.
- **Detailed explanations** of the role of weights, biases, and activation functions.
- Step-by-step breakdown of how the network processes inputs to produce an output.

## Project Goal

The goal of this project is to provide beginners with a clear and hands-on introduction to how neural networks work at a fundamental level. By the end of the notebook, you will understand:
- What weights and biases are and how they influence a network’s output.
- The importance of activation functions and how they introduce non-linearity.
- How a network processes input data using forward propagation.

## Setup Instructions

If you want to run the notebook on your local machine, follow the instructions below to set everything up.

### Prerequisites

To run this notebook, you’ll need:
- **Python 3.x** installed on your machine.
- **Jupyter Notebook** installed.

If you don’t have Jupyter Notebook installed, follow these steps to set it up:

1. **Install Jupyter via pip:**

    ```bash
    pip install notebook
    ```

2. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    cd your-repo-name
    ```

3. **Launch Jupyter Notebook:**

    ```bash
    jupyter notebook
    ```

4. Open the notebook file (`Forward-Propagation.ipynb`) from the Jupyter interface and explore the code and explanations.

## How the Neural Network Works

This neural network uses a basic architecture with one hidden layer to perform a simple task of binary classification. Here's a summary of the process:

1. **Input Layer**: The input layer receives two inputs. These could be features like pixel values from an image or any other data.
  
2. **Hidden Layer**: The hidden layer contains two neurons. Each neuron processes the input data by calculating a weighted sum of the inputs, adding a bias, and then applying an activation function (sigmoid) to determine its output.

3. **Output Layer**: The output layer contains a single neuron that takes the outputs of the hidden layer, calculates a weighted sum, adds a bias, and applies the sigmoid activation function to produce the final prediction.

### Forward Propagation

- **Step 1: Weighted Sum**: Each neuron multiplies its inputs by its corresponding weights and calculates a weighted sum.
- **Step 2: Add Bias**: A bias is added to the weighted sum, allowing the network to adjust its output.
- **Step 3: Apply Activation Function**: The sigmoid activation function is applied to introduce non-linearity, which enables the network to learn complex patterns.
- **Step 4: Output**: The output of the final neuron represents the network’s prediction, usually a value between 0 and 1, indicating the probability of a certain outcome.

## Example Usage

If you run the notebook, you will see step-by-step explanations of how the network processes the input data. Here's a quick look at how you can run the notebook:

- **Modify the Inputs**: Try changing the input values and observe how the network's output changes.
- **Explore Weights and Biases**: Experiment with different weights and biases to see how they affect the output.
- **Understand Forward Propagation**: Follow the detailed explanations in each cell to get a solid grasp of how forward propagation works.

## Contributing

Contributions are welcome! If you have suggestions for improving this project, feel free to submit a pull request or open an issue. Together, we can make this repository even better for beginners.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
