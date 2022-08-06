# Computer-Vision
 
## [Improve MNIST with Convolutions](https://github.com/MarcoStallmann/Computer-Vision/blob/ef85b000513f0c9d6d52e99181ccafdebff48d10/Improve%20MNIST%20with%20Convolutions/improve_mnist_with_convolutions.ipynb)

For this exercise we see if we can improve MNIST to 99.5% accuracy or more by adding only a single convolutional layer and a single MaxPooling 2D layer to the model. We stop training once the accuracy goes above this amount. It should happen in less than 10 epochs, so it's ok to hard code the number of epochs for training, but our training must end once it hits the above metric. If it doesn't, then we'll need to redesign your callback. When 99.5% accuracy has been hit, we print out the string "Reached 99.5% accuracy so cancelling training!"
