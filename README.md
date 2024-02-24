# Hw6

The provided code defines a simple neural network for binary classification with two hidden layers (20 and 4 neurons) using the ReLU activation function. The model is compiled with the Adam optimizer and binary crossentropy loss. Training occurs for 100 epochs, and the model is evaluated on test data. The summary prints the architecture details, and the final evaluation results (loss and accuracy) are displayed.

Dataset Loading:

MNIST dataset is loaded, and class labels are converted to binary class matrices.
Model Architectures:

Four models are created with different architectures:
Model 1: 1 hidden layer with tanh activation
Model 2: 1 hidden layer with sigmoid activation
Model 3: 2 hidden layers with tanh activation
Model 4: 2 hidden layers with sigmoid activation
Training:

Each model is compiled using categorical crossentropy loss and the Adam optimizer.
Training is performed for 20 epochs, and loss and accuracy curves are plotted for both training and validation sets.
Evaluation:

The models are evaluated on the test data, and the test loss and accuracy are printed.
This code provides a comparative analysis of different neural network architectures and activation functions on the MNIST dataset. It visually presents the training and validation curves for each model and reports the test accuracy after training.





