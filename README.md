# Basic Neural Network using numpy
Simple neural network that is trained to recognise digits from the mnist dataset.

The input was taken as a in the form of 784 neurons with each neuron having the pixel value of a pixel from the image(28 x 28 = 784)

It has 2 hidden layers, the first hidden layer uses ReLU activation and the second layer uses tanh activation.

The output layer is softmax, for which the categorical cross entropy loss is evaluated.

This network will optimise accuracy by minimising the algebraic difference between the predicted matrix and the true matrix, using gradient descent and the upating the weights and biases in accordsance with the gradients and the learning rate.

The learning rate of 0.15 was found to give the best results and an accuracy of roughly 85% was reached in 500 epochs.
The weights and biases were initilaised to random values between -0.5 and 0.5.
