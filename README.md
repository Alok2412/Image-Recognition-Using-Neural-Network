# Image-Recognition-Using-Neural-Network
Python Code to Perform the Image Recognition Using Keras 

Image recognition is performed by feeding an image into a neural network and getting the output some kind of label for that image. The label that the network outputs will correspond to a pre-defined class. There can be multiple classes that the image can be labeled as, or just one.

In order to carry out image recognition/classification, the neural network performs feature extraction. Features are the elements of the data that you care about which will be fed through the network. In the specific case of image recognition, the features are the groups of pixels, like edges and points, of an object that the network will analyze for patterns.

Feature recognition (or feature extraction) is the process of pulling the relevant features out from an input image so that these features can be analyzed. Many images contain annotations or metadata about the image that helps the network find the relevant features.
In this example, we will be using the CIFAR-10 dataset. CIFAR-10 is a large image dataset containing over 60,000 images representing 10 different classes of objects like cats, planes, and cars.

The images are full-color RGB, but they are fairly small, only 32 x 32. One great thing about the CIFAR-10 dataset is that it comes prepackaged with Keras, so it is very easy to load up the dataset and the images need very little preprocessing.

# References:
[1] Dan Nelson

[2] For DataSet: Learning Multiple Layers of Features from Tiny Images, Alex Krizhevsky, 2009.
