# Machine-Learning-Models-from-Scratch

```A collection of Machine Learning Models Made from Scratch. These models were created while solving questions on the following topics.```


1. Feature Reduction using Principle Component Analysis

2. Image Classification using Convolution Neural Network
------------------------------------------------------------------------------------------------------

**Principal Component Analysis**


PCA (principal component analysis) on the Iris dataset and reduce it to 3 features and 2
features.

**Output:** Two reduced dimension matrices (150 by 3) and (150 by 2) and data plot

--------------------------------------------------------------------------------------------------------

**Image Classification using Convolution Neural Network**

  ```Model Accuarcy: 72%```


 **Dataset:** CIFAR10 dataset
(download https://www.cs.toronto.edu/ kriz/cifar-10-python.tar.gz)
The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images
per class. There are 50000 training images and 10000 test images.
The dataset is divided into ve training batches and one test batch, each with 10000 images.
The test batch contains exactly 1000 randomly-selected images from each class. The training
batches contain the remaining images in random order, but some training batches may contain
more images from one class than another. Between them, the training batches contain exactly
5000 images from each class.


 **Classes:** The dataset consists of 10 classes {`airplane', `automobile', `bird', `cat', `deer', `dog',
`frog', `horse', `ship', `truck'}

**Process**

  1. Loading and normalizing the CIFAR10 training and test datasets using torchvision.
  
  2. Convolution layers, max pooling, and 3 layers for feed-forward network.
  
  3. A loss function
  
  4. An optimizer
  
  5. Training the network on the training data and save the model
  
  6. Testing the network on the test data
  
  
