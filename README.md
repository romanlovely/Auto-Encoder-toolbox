# Auto-Encoder-toolbox
This is the Auto-Encoder toolbox for the paper "Fengling Mao, Wei Xiong, Bo Du and Lefei Zhang. Stochastic Decorrelation Constraint Regularized Auto-Encoder for Visual Recognition. MultiMedia Modeling(MMM). Springer International Publishing, 2017" -- Fengling Mao.

@inproceedings{mao2017stochastic, </br>
title={Stochastic decorrelation constraint regularized auto-encoder for visual recognition},</br>
author={Mao, Fengling and Xiong, Wei and Du, Bo and Zhang, Lefei},</br>
booktitle={International Conference on Multimedia Modeling (MMM)}, </br>
pages={368--380}, </br>
year={2017},</br>
organization={Springer}</br>
}



<font size=8> **Introduction** </font>

1. A matlab toolbox for Auto-Encoder with whitening, convolution, pooling, classification.

2. This Auto-Encoder toolbox is programmed based on the Deep Learn Toolbox (https://github.com/rasmusbergpalm/DeepLearnToolbox).

3. The simple example of using this toolbox is a small experiment of our paper-"Stochastic Decorrelation Constraint Regularized Auto-Encoder for Visual Recognition" on the MNIST dataset.


<font size=8>  **Run Step** </font>

1. download the MNIST dataset (http://yann.lecun.com/exdb/mnist/), and put the 'mnist_uint8.mat' into the 'data' folder.  
2. addpath the toolbox.
3. open the initL2.m to initialize the network parameters.
4. run the DAE_MNIST.m.
5. we add the Stochastic Decorrelation Constraint Regularizer in AEcost.m
