# The Deep Learning Cookbook

We all know and love the [Matrix Cookbook](http://www2.imm.dtu.dk/pubdb/views/edoc_download.php/3274/pdf/imm3274.pdf), and now the world also has a Deep Learning Cookbook!

This repo will contain simple recipes to achieve given goals using (Deep) Neural Networks. Some code implementations in keras will be made available.

So here I will talk about convnets, batch normalisation, LSTM, GRU, dropout, pseudolabelling, different optimisers, style transfer, text generation, GANs, and more!

You can contribute to this repo if you want.

## Predict data using a linear model

Use ~~linear regression~~ a single layer perceptron with no activation function. This will be a simple function that multiplies your inputs by a weight matrix and outputs that.

# Regularising a neural network

# What gradient descent optimiser should I use?

Short answer: Adam.
Long answer: read [this](http://sebastianruder.com/optimizing-gradient-descent/) and [this](https://medium.com/slavv/picking-an-optimizer-for-style-transfer-86e7b8cba84b#.mm98exrzp)

# I cannot sleep because I don't know what is the best CNN architecture for image recognition
Do you want the best at any cost? Then use Inception V4

Do you want the most efficient net in terms of parameters? Then use ENet, it is 6 times as efficient as Inception

Andrej Karpathy has a review of some architectures [here](http://cs231n.github.io/convolutional-networks/#overview)

[Here](https://culurciello.github.io/tech/2016/06/04/nets.html) there is a comparison between the architectures Karpathy mentions, and more. The author also has a more recent paper [here](https://arxiv.org/pdf/1605.07678.pdf)

# There are so many activation functions! Which one do I use?
ReLUs is what cool kids are all about these days. If you feel adventurous, try Leaky or Parametric ReLUs or ELUs.

