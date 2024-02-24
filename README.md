# Hw6

Summary:

Dataset Loading:

MNIST dataset loaded.
Pixel values normalized to the range [0, 1].
Model Architectures:

Four models created with different architectures:
Model 1: 1 hidden layer with tanh activation.
Model 2: 1 hidden layer with sigmoid activation.
Model 3: 2 hidden layers with tanh activation.
Model 4: 2 hidden layers with sigmoid activation.
Training:

Models compiled with categorical crossentropy loss and Adam optimizer.
Trained for 20 epochs.
Loss and accuracy curves plotted for training and validation sets.
Evaluation:

Models evaluated on the test data.
Test loss and accuracy printed.
Additional Step:

Pixel Normalization:
Pixel values of the images in the MNIST dataset are normalized to the range [0, 1] by dividing by 255.
This code provides a comprehensive analysis of different neural network architectures and activation functions on the MNIST dataset, including normalization of pixel values to enhance training performance. The training and validation curves are visualized, and test accuracy is reported for each model.

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





