# Deep learning projects

## Overview 

This repository contains some of projects I achieved  in order to learn about neural networks. It focus on deep-learning, using different types of neural networks and approaches .

## Project 1:

The project 1 focus on building a Neural Network to predict the number of bikeshare users on a given day. Imagine yourself owning a bikesharing company. You want to predict how many bycles you need because if they are too few, you will loose money from potential rides, if they are too many, you will waste money on buying cycles just settled around.  You need to predict from historical datas how money bycles you will need to buy in the future.
![bikesharing](https://github.com/virt87/DeepLearning/blob/master/Bikeshare-neural-network/bikesharing.png)

### Dependencies

* Download anaconda
* Create a new conda environment:
```
conda create --name bikesharing python=3
```
* Activate the source
```
source activate bikesharing
```
* Ensure you have numpy, matplotlib, pandas, and jupyter notebook installed by doing the following:
```
conda install numpy matplotlib pandas jupyter notebook
```
* Run the following to open up the notebook:
```
jupyter notebook bikesharing-neural-network.ipynb
```
### Take a look
You can open the jupyter notebook directly in github [bikesharing-neural-network.ipynb](https://github.com/virt87/DeepLearning/blob/master/Bikeshare-neural-network/bikesharing-neural-network.ipynb)

## Project 2:
Sentiment analysis with Andrew Trask. The main focus of this project is to understand how to create a neural network that can anlyse a review and classify it as bad or good.
It is split into several parts:
- curating a data set.
- training a a neural network
- increasinghe signal and reducing the noise in teh data set.

### Dependencies

* Download anaconda
```
conda create --name sentiment_alysis python=3
```

* Activate the source
```
source activate sentiment_alysis
```
* Ensure you have numpy, jupyter notebook, matplotlib, scikit-learn, and bokeh installed by doing the following:
```
conda install numpy matplotlib  jupyter notebook scikit-learn bokeh
```
* Run the following to open up the notebook:
```
jupyter notebook Sentiment\ Classification.ipynb
```


### Take a look
You can open the jupyter notebook directly in github [Sentiment Classification.ipynb](https://github.com/virt87/DeepLearning/blob/master/Sentiment analysis/Sentiment Classification.ipynb)


## Project 3:
Sentiment analysis with TFLearn. The same work as the previous project by now using TFLearn.

### Dependencies

* Download anaconda
```
conda create -n tflearn python=3.5
```

* Activate the source
```
source activate tflearn
```
* Ensure you have numpy, jupyter notebook, matplotlib and pandas.
```
conda install numpy pandas jupyter notebook matplotlib
```
* Run the following to open up the notebook:
```
jupyter notebook Sentiment\ Analysis\ with\ TFLearn.ipynb
```

### Take a look
You can open the jupyter notebook directly in github [Sentiment Analysis with TFLearn.ipynb](https://github.com/virt87/DeepLearning/blob/master/TFLearn/sentiment-analysis/Sentiment Analysis with TFLearn.ipynb)



## Project 4:
Handwritten digit recognition with TFLearn. Using the [MNIST](http://yann.lecun.com/exdb/mnist/) dataset, which contains images of handwitten single digits and their respective lavels (numbers from 0 to 9), we train a neuronal network that recognizes handwritten digits.

### Dependencies

* Download anaconda
```
conda create -n tflearn python=3.5
```

* Activate the source
```
source activate tflearn
```
* Ensure you have numpy, jupyter notebook, matplotlib and pandas.
```
conda install numpy pandas jupyter notebook matplotlib
```
* Run the following to open up the notebook:
```
jupyter notebook Handwritten\ Digit\ Recognition\ with\ TFLearn.ipynb
```

### Take a look
You can open the jupyter notebook directly in github 
[Handwritten Digit Recognition with TFLearn.ipynb](https://github.com/virt87/DeepLearning/blob/master/TFLearn/Handwritten%20Digit%20Recognition/Handwritten%20Digit%20Recognition%20with%20TFLearn.ipynb)

## Project 5:
In this project, I'll classify images from the [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset. The dataset consists of airplanes, dogs, cats, and other objects. The dataset will need to be preprocessed, then train a convolutional neural network on all the samples. I'll normalize the images, one-hot encode the labels, build a convolutional layer, max pool layer, and fully connected layer. At then end, I'll see their predictions on the sample images.

As an exercise, this project will run on a machine with GPU using floydhub.com.

### Take a look
You can open the jupyter notebook directly in github [Image Classification](https://github.com/sbatururimi/DeepLearning/blob/master/Image%20Classification/dlnd_image_classification.ipynb)


## Project 6:
In this project, I played with a Recurrent Neural network implementing LSTM cells in order to generate my own Simpsons TV script. I used a part of the Simpsons dataset of scripts from 27 seasons. The Neural Network I built  generate a new TV script for a scene at Moe's Tavern. The RNN was trained on GPU using FloydHub.

In order to run it, setup Conda, then activate an environment:
```
$ conda env create -f environment.yaml
```
Setup floyd hub and launch it in GPU mode:
```
$ floyd login
$ floyd init
$ floyd run --mode jupyter --gpu
```

### Take a look
You can open the jupyter notebook directly in github 
 [TV script generation with RNN](https://github.com/sbatururimi/DeepLearning/blob/master/tv-script-generation/dlnd_tv_script_generation.ipynb)

## Project 7:
A case study of Transfer Learning.

In practice, you won't typically be training your own huge networks. There are multiple models out there that have been trained for weeks on huge datasets like ImageNet. In this project, I'll be using one of these pretrained networks, VGGNet, to classify images of flowers.

[Transfer Learning](https://github.com/sbatururimi/DeepLearning/blob/master/transfer-learning/Transfer_Learning.ipynb)

## Project 8:

A languag translation project using Sequence to Sequence model. It has been trained on  GPU, using Floyd.
This Sequence to Sequence model is trained on a dataset of English and French sentences and can translate new sentences from English to French.

[Language translation](https://github.com/sbatururimi/DeepLearning/blob/master/language-translation/dlnd_language_translation.ipynb)


## Project 9: 
Building an Autoencoder Neural network to compress and denoise images

[Compress without convolutions](https://github.com/sbatururimi/DeepLearning/blob/master/autoencoder/Simple_Autoencoder.ipynb)

[Compress and denoise with convolutions](https://github.com/sbatururimi/DeepLearning/blob/master/autoencoder/Convolutional_Autoencoder.ipynb)

## Project 10:
Training a GAN on MNIST to generate new handwritten digits

[A generative adversarial network (GAN) trained on the MNIST dataset.](https://github.com/sbatururimi/DeepLearning/blob/master/gan_mnist/Intro_to_GANs_Exercises.ipynb)


## Project 11:
A simple case study of the batch normalization for normalizing the inputs to layers within the network.

[Batch normalization](https://github.com/sbatururimi/DeepLearning/blob/master/batch-norm/Batch_Normalization_Lesson.ipynb)


## Project 12:
Building a  Deep Convolutional GAN, i.e DCGAN, using convolutional layers in the generator and discriminator. I'll be training DCGAN on the [Street View House Numbers](http://ufldl.stanford.edu/housenumbers/) (SVHN) dataset. These are color images of house numbers collected from Google street view. SVHN images are in color and much more variable than MNIST.



## Project 13:
Training a DCGAN on CelebA to generate new images of human faces

[A generative adversarial network (GAN) trained on the CelebA dataset.](https://github.com/sbatururimi/DeepLearning/blob/master/face_generation/dlnd_face_generation.ipynb)

## Project 14:
Training a semi-supervised GAN for the SVHN (Street View House Numbers) dataset to generate new images and attempt to classify the images with a large proportion of the labels dropped.
[Semi-supervised Learning.](https://github.com/sbatururimi/DeepLearning/blob/master/semi-supervised/semi-supervised_learning_2.ipynb)

