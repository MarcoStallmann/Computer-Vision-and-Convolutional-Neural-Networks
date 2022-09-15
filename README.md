# Computer-Vision

*by Marco Stallmann*

## [Digit recognizer](https://github.com/MarcoStallmann/Computer-Vision/blob/main/Digit%20recognizer%20analysis/digit-recognizer-comparative-analysis.ipynb)

In the Kaggle Digit Recognizer competition, the goal is to correctly identify digits from a dataset of tens of thousands of handwritten images (MNIST). Kaggle has curated a set of tutorial-style kernels which cover everything from regression to neural networks and encourages to experiment with different algorithms and are therefore incorporated into this Notebook with reference.


## [Improve MNIST with Convolutions](https://github.com/MarcoStallmann/Computer-Vision/blob/ef85b000513f0c9d6d52e99181ccafdebff48d10/Improve%20MNIST%20with%20Convolutions/improve_mnist_with_convolutions.ipynb)

For this exercise we see if we can improve MNIST to 99.5% accuracy or more by adding only a single convolutional layer and a single MaxPooling 2D layer to the model. We stop training once the accuracy goes above this amount. It should happen in less than 10 epochs, so it's ok to hard code the number of epochs for training, but our training must end once it hits the above metric. If it doesn't, then we'll need to redesign your callback. When 99.5% accuracy has been hit, we print out the string "Reached 99.5% accuracy so cancelling training!"


## [Transfer Learning with Hourses or Humans Dataset](https://github.com/MarcoStallmann/Convolutional-Neural-Networks/blob/ede22460ce3ab4238d9df9f47395581f3930781e/Transfer%20Learning%20with%20Horse%20or%20Human%20Dataset/Transfer%20Learning%20with%20Horse%20or%20Human%20Dataset.ipynb)

Here we are going to use Transfer Learning which utilizes an already trained network to help us solve a similar problem to the one it was originally trained to solve.
