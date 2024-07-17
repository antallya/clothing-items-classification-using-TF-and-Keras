## MNIST-Fashion Classification with TensorFlow and Keras
At one of the workshops of the Mexico SIAM (Society for Industrial and Applied Mathematics) convention in 2022, I learned how to use TensorFlow API and Keras library in Python to train a sample in MNIST-fashion by Zalando. 

### Dataset content
Some specifics of this dataset are listed as follows:
* There are 60,000 images in the training set, with each image represented by 28×28 bitmaps (matrices)
* There are 60,000 labels for training
* Each label is an integer between 0−9

### Statistical 
1. Loss function: Measures how accurate the model is during training. The idea is to minimize this function.
2. Optimizer: The optimizer determines how the model is updated based on the data input and the cost function. We are using: gradient descent.
3. Metrics: Metrics are used to monitor the training and testing steps.

We used accuracy, which is the fraction of images that are correctly classified.
