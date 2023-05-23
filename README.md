# MNIST Classification with Neural Network

This project focuses on developing a multi-layer neural network using only numpy for classification on the MNIST dataset. The goal is to implement various layers, regularization techniques, and an optimizer to train and evaluate the neural network's performance. The following tasks need to be accomplished:

## 1. Layer Implementations

### Sigmoid Layer
- Implement a sigmoid activation layer with forward and backward pass methods.
- The forward pass computes the sigmoid activation for the input and stores the intermediate values needed for the backward pass.
- The backward pass calculates the gradient with respect to the input and updates the layer's parameters.

### ReLU Layer
- Implement a ReLU activation layer with forward and backward pass methods.
- The forward pass applies the rectified linear unit activation function to the input and stores relevant values for the backward pass.
- The backward pass computes the gradient based on the input and updates the layer's parameters.

### Softmax Output Layer
- Implement a softmax activation layer as the output layer for classification.
- The forward pass computes the softmax probabilities for the input and stores necessary values for the backward pass.
- The backward pass calculates the gradient of the loss function with respect to the input and updates the layer's parameters.

### Dropout or Regularization
- Implement a regularization technique like dropout to prevent overfitting in all layers.
- Include methods for applying dropout during the forward pass and adjusting the gradients during the backward pass.

## 2. Layer Testing

- Develop a test suite to verify the correctness of each layer's forward and backward pass methods.
- Use various input values and expected output values to validate the implementations.
- Ensure that the gradients are correctly calculated and updated during the backward pass.

## 3. Parameterizable Neural Network

- Create a fully parameterizable neural network class that can accommodate different layer types, numbers, and units.
- Allow the flexibility to define the architecture of the network by specifying the number and types of layers, as well as the number of units in each layer.
- Include methods for forward propagation, backward propagation, and parameter updates.

## 4. Optimizer and Stopping Criterion

- Implement an optimizer such as Stochastic Gradient Descent (SGD) or Adam to update the network parameters during training.
- Develop a stopping criterion that determines when to stop the training process based on certain conditions, such as reaching a maximum number of epochs or achieving satisfactory performance.

## 5. Evaluation and Results

- Evaluate different neural network architectures and parameters on the MNIST dataset.
- Present and discuss the results of the experiments, including accuracy, loss, and other relevant metrics.
- Analyze the impact of changing the number and types of layers, the number of units, and the regularization techniques on the network's performance.
- Provide insights and conclusions based on the experimental findings.

## Conclusion

This project aims to develop a fully functional neural network for classification on the MNIST dataset using only numpy. By implementing various layers, regularization techniques, and an optimizer, you will gain a deeper understanding of the fundamental concepts behind neural networks and their impact on classification performance. Remember to thoroughly test each component and carefully analyze the results to draw meaningful conclusions about the network's behavior and the effect of different architectural choices and hyperparameters.
