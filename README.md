# MNIST Classification (One vs All + 10-class classification)

In this notebook, I implement logistic regression from scratch on the MNIST Dataset. I add in some extra features like: 
* Mini-batch training
* L2 Regularization

First, 10 Logistic regression models are trained to do one vs all classifications (digit 0, digit 1, ... etc), then they are all used to predict one of ten classes using highest probability output

N.B: the mnist-original.mat is too big to put in the repository. The .mat file can be readily found online. Simply downloading it and keeping it in the same directory as the notebook should suffice
