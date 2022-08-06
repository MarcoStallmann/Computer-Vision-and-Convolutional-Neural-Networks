# Computer-Vision

## [Implementing Callbacks in TensorFlow using the MNIST Dataset](https://github.com/MarcoStallmann/Computer-Vision/blob/04ae0ed3cad36040b7d195c22bdb007b4aafe0c5/Implementing%20Callbacks%20in%20TensorFlow%20using%20the%20MNIST%20Dataset/Implementing_Callbacks_in_TensorFlow_using_the_MNIST_Dataset.ipynb)

Here we are practicing classification MNIST which has items of handwriting -- the digits 0 through 9. We write an MNIST classifier that trains to 99% accuracy and stops once this threshold is achieved. 

 
## [Improve MNIST with Convolutions](https://github.com/MarcoStallmann/Computer-Vision/blob/ef85b000513f0c9d6d52e99181ccafdebff48d10/Improve%20MNIST%20with%20Convolutions/improve_mnist_with_convolutions.ipynb)

For this exercise we see if we can improve MNIST to 99.5% accuracy or more by adding only a single convolutional layer and a single MaxPooling 2D layer to the model. We stop training once the accuracy goes above this amount. It should happen in less than 10 epochs, so it's ok to hard code the number of epochs for training, but our training must end once it hits the above metric. If it doesn't, then we'll need to redesign your callback. When 99.5% accuracy has been hit, we print out the string "Reached 99.5% accuracy so cancelling training!"
