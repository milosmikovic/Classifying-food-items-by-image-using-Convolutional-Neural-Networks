# Classifying food items by image using Convolutional Neural Networks

## Team members:

Milos Mikovic 1050/2020


Literature: http://cs231n.stanford.edu/reports/2017/pdfs/607.pdf


# About The Project
The Freiburg Groceries
Dataset is a dataset consisting of 4,947 256x256 RGB
images covering 25 different classes of groceries, with at
least 97 images per class. Images are collected from real-world settings at different stores and apartments. In contrast to existing groceries datasets,
dataset includes a large variety of perspectives, lighting conditions, and degrees of clutter. 
All models are made with image rescaling to 150x150(x3) due to hardware limitations. The CNN architectures used are: vgg16, vgg19, alexNet, resNet. 
All models ipynb files are almost identical but contain different models and were added to display different model results.

Models: alexNet.ipynb, resNet150v2.ipynb, vgg16.ipynb, vgg19.ipynb

Simple model testing: testModels.ipynb

Testing different output layers of vgg16 (with some hyperparameter tuning) and their results: vgg16NetMaker.ipynb


# Technologies used
Codding language is [Python](https://www.python.org/)

Code was written using [Anaconda](https://www.anaconda.com/) and [Jupyter Notebook](https://jupyter.org/)

Other packages and libraries used: [Keras](https://keras.io/), [Matplotlib](https://matplotlib.org/), [Numpy](https://numpy.org/), [Scipy](https://www.scipy.org/), 
[OpenCV](https://opencv.org/), [Scikit-Learn](https://scikit-learn.org/stable/)

## Dataset location
Location: http://aisdatasets.informatik.uni-freiburg.de/freiburg_groceries_dataset/

# CNN architectures

## ResNet 150v2

model: https://drive.google.com/drive/folders/1sHzLdx-7-1xX-GiQXFrhyt4ISd589Edp?usp=sharing

model weigths: https://drive.google.com/drive/folders/1fKk78iX7MYWhw6OVYpj7kRwPkXC9u-Jo?usp=sharing

## VGG16 and VGG19
Model and model weigths are added to repository

## AlexNet

model: https://drive.google.com/drive/folders/1HsLrszkibgDbZVr4I0F3xbAXTU3uahFu?usp=sharing

model weigths: https://drive.google.com/drive/folders/10ZR7SjQchh4BNpmxekRqavdEQhCxFIbF?usp=sharing
