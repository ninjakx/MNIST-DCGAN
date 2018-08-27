# MNIST-DCGAN
Keras Implementation of DCGAN.


## Network Architecture
![Model](https://gluon.mxnet.io/_images/dcgan.png)

### Generator
hidden layers: Four 4x4 strided convolutional layers (1024 , 512, 256, and 128 kernels, respectively) with ReLU.
output layer: 4x4 strided convolutional layer (4096 nodes = 64x64 size image) with Tanh.
Batch normalization is used.

### Discriminator
hidden layers: Four 4x4 convolutional layers (128, 256, 512, and 1024 kernels, respectively) with Leaky ReLU.
output layer: 4x4 convolutional layer (1 node) with Sigmoid.
Batch normalization is used.


Images are resized to 28x28 size.

## Results
![results](https://github.com/ninjakx/MNIST-DCGAN/blob/master/result.png)
