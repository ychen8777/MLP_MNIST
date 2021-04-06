## Multilayer perceptron classifier on MNIST dataset

In this project, we implemented and examined performance of multilayer perceptron on MNIST dataset.

The goal for training the model is to minimize the multi-class cross entropy loss. This is done by mini-batch gradient descent.

We tried to narrow down the range of learning rates for gradient descent by demonstrating their effects on the loss function during the training process:

![Loss Graph](/figures/loss_curves_v4.png)

To prevent overfitting, we tracked train and test accuracies as training continues:


![Train-Test Accuracy_ReLu](/figures/train_test_relu.png)

![Train-Test Accuracy_Sigmoid](/figures/train_test_sigmoid.png)

With a model of 2 hidden layers, 128 neurons in each layer, we received the below cross-validation and test results:

![Results_Table](/figures/results_table.png)
