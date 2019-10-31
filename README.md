# Image Classification with CIFAR-10 dataset

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images. 

The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly-selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class. 

Here are the classes in the dataset, as well as 10 random images from each:
- airplane										
- automobile										
- bird										
- cat										
- deer										
- dog										
- frog										
- horse										
- ship										
- truck

# Model Architecture

MiniGoogLeNet which includes a simplified version of the Inception module from Szegedy et al.’s seminal [Going Deeper with Convolutions](https://arxiv.org/abs/1409.4842) paper:
![image](keras_3_model_types_minigooglenet.png)