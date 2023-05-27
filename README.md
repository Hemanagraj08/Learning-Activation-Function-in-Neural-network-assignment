# Learning-Activation-Function-in-Neural-network-assignment

Learning Activations in Neural Networks


A neural network’s architecture is derived from the structure of a human brain while from a mathematical point of view, it can be understood as a function which maps a set of inputs to desired outputs.
Neural Networks, also known as artificial neural networks which is used for solving artificial intelligence problems. Multilayer perceptron is a class of artificial neural network that uses back propagation technique for training by updating the weights accordingly, it consists of three layers called input layers, hidden layers, output layers. 
Here we will give an example of creating neural network in python using sigmoid as activation function, forward propagation with one hidden layer and back propagation in this report. During training all the weights and biases are updated after processing single training sample. The activation function is sigmoid of the form f(x)=1/1+exp(-x) it ranges between 0 and 1. Iris dataset is used to train the neural network with three different targets for the output. The number of epochs was set to 3000, with learning rate of 0.01.
Backpropagation is employed to train the neural network. The backpropagation algorithm updates the weights in the neural network by first calculating the gradient of the loss function with respect to each weight. Firstly we used Forward propagation technique to determine the output values for each samples in the training set   by calculating the error value and back propagating which uses chain rule to determine the gradient of the loss with respect to each weight in the neural network. Updates the neural network by updating the adjusted weights which is obtained through back propagation. This process is carried out through out the training process until the weight is updated in neural network for given number of epochs.


Three categories were predicted from the output.
epoch: 1Error: 0.7898213091833823
epoch: 201Error: 0.6662060411002394
epoch: 401Error: 0.4012679961269656
epoch: 601Error: 0.37547583276407664
epoch: 801Error: 0.36562992108687126
epoch: 1001Error: 0.36001071479259655
epoch: 1201Error: 0.35610421913136503
epoch: 1401Error: 0.35321297727337486
epoch: 1601Error: 0.3510489673225294
epoch: 1801Error: 0.34936262078030195
epoch: 2001Error: 0.3480022634571566
epoch: 2201Error: 0.34688168580024314
epoch: 2401Error: 0.3459448337111483
epoch: 2601Error: 0.3451516624612308
epoch: 2801Error: 0.34447241044334004
 
The error decreased with each epoch, indicating that the neural network was learning to classify the input data accurately.

