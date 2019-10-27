# Residual-Networks-CNN

This project deals with building ResNet50 network from scratch using helper funcitons to classify an image in to one of 6 categories.
It is part of Deep learning specialization in coursera but I extended the project by training the model on GPU's for more number of 
epochs.

_Code is written in Tensorflow-Keras.

## Data

**SIGNS** dataset is a collection of 6 hand signs representing numbers from 0 to 5.

You can find sample of how data looks like in [here](https://github.com/raviteja-ganta/Residual-Networks-CNN/tree/master/Images)

Goal is to classify image in to 6 catgories.

* 1) 0
* 2) 1
* 3) 2
* 4) 3
* 5) 4
* 6) 5

We have two sets of data:

* Train data
* Test data

Train data is for traning Conv net. Test data(in this case used as validation data) is for selecting best model.
Data is included with this repo.

## Contents

Jupyter notebook has following contents in order to build model and also for selecting best hyperparameters.
* 1) The problem of very deep neural networks
* 2) Identity block
* 3) Convolutional block
* 4) Building first ResNet model (50 layers)
