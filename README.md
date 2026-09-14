# Deep Learning and Probabilistic Models Lab

This repository gathers the notebooks and practical work from the Data Science option, covering neural network architectures and probabilistic modeling.

## Contents

### TP-reseaux denses
Introduction to feed forward neural networks (also known as multi layer perceptrons or dense neural networks), built with Keras and PyTorch. Covers forward and backward propagation, the chain rule, and how these networks handle nonlinear regression and classification tasks. Includes a small housing dataset (DPE) and a heating consumption dataset used for the exercises.

### TP-reseaux CNN
Introduction to convolutional neural networks with Keras. Covers convolution and max pooling operations, filters and kernels, and closes with a look at the VGG-16 architecture.

### IntroductionToVAE.ipynb
Introduction to variational autoencoders, implemented with Jax and applied to the Fashion MNIST dataset. Based on Kingma and Welling's tutorial paper on VAEs.

### recurrent_neural_networks.ipynb
Introduction to recurrent neural networks and LSTMs, the first architectures built to handle sequential, time dependent data.

### transformers.ipynb
Introduction to transformer networks and attention based models, starting from the original "Attention is all you need" paper and building up to layer normalization and the transformer architecture.

### VI_basics.ipynb
Introduction to variational inference: the evidence lower bound (ELBO) and coordinate ascent variational inference (CAVI), worked through on a Gaussian mixture example.

## Requirements

The notebooks rely on standard Python data science and deep learning libraries, including Keras, PyTorch, and Jax depending on the notebook. Each notebook lists its own references and further reading in its introduction section.
