### Backpropagation Algorithm for XOR Classification

This program implements a **simple feedforward neural network using the backpropagation algorithm** to solve the **XOR problem**. The model is built from scratch using **Python and NumPy**.

The XOR dataset is not linearly separable, so a **hidden layer** is required for the network to learn the pattern.

**Network Architecture**
- Input Layer: 2 neurons  
- Hidden Layer: 2 neurons  
- Output Layer: 1 neuron  

The network uses the **Sigmoid activation function**:

f(x) = 1 / (1 + e^-x)

Training is performed using **forward propagation** to compute predictions and **backpropagation** to update weights and biases based on the error.

After sufficient training iterations, the network learns to correctly approximate the XOR outputs.
