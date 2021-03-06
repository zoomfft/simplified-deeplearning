# Simplified DeepLearning
Quick and dirty implementations of some interesting works related to deep learning.
Contribution is always welcome, you could just add links to your repository.

You may use any of the deep learning frameworks, such as pytorch, theano, mxnet and tensorflow.
However, you should keep the implementation as simple as possible. 


## Gradient Descent


## Regression


## MLP from scratch


## Regularization


## SGD Comparison
Comparison of various SGD algorithms on logistic regression and MLP. The relation of these algorithms is shown in the following figure, please refer to [sgd-comparison](https://github.com/SwordYork/simplified-deeplearning/tree/master/sgd-comparison) for the details. 
<p align="center">
<img src="/sgd-comparison/figures/relation.png?raw=true" width="80%">
</p>


## Newton Method


## Neural Style
Refer to [jcjohnson](https://github.com/jcjohnson/neural-style).


## Function Approximation
Use neural network to approximate functions. The approximated functions are shown in the following figures, please refer to [function-approximation](https://github.com/SwordYork/simplified-deeplearning/tree/master/function-approximation) for the details. 
<p align="center">
<img src="/function-approximation/figures/lovefunc.png?raw=true" width="45%">
<img src="/function-approximation/figures/sinxx.png?raw=true" width="45%">
</p>


## Char-RNN
Refer to [karpathy](https://github.com/karpathy/char-rnn) or [johnarevalo](https://github.com/johnarevalo/blocks-char-rnn).

## POS Tagging


## Sequence to Sequence
It is really hard to simplify because of the attention mechanism.
We have try our best to simlify the encoder-decoder architecture, which is demonstrated in the following figures.
<p align="center">
<img src="https://raw.githubusercontent.com/SwordYork/sequencing/master/docs/figures/encoder.jpg" width="45%">
<img src="https://raw.githubusercontent.com/SwordYork/sequencing/master/docs/figures/decoder.jpg" width="45%">
</p>

Please refer to [Sequencing](https://github.com/SwordYork/sequencing) for more details.


## PCA, PPCA


## Autoencoder
Refer to [Keras](https://blog.keras.io/building-autoencoders-in-keras.html).


## Word Embedding


## MCMC


## RBM

## Generative Adversarial Networks 
A simple demonstration of Generative Adversarial Networks (GAN), maybe problematic. 
<p align="center">
<img src="/GAN/figures/gaussian.png?raw=true" width="45%">
<img src="/GAN/figures/training.gif?raw=true" width="45%">
</p>

According to the [paper](https://arxiv.org/abs/1406.2661), we also use GAN to generate Gaussian distribution which shown in the left figure. Then we try to generate digits based on MNIST dataset, however, we encouter "the Helvetica scenario" in which G collapses too many values of z to the same value of x. Nevertheless, it is a simple demonstration, please see the [details](https://github.com/SwordYork/simplified-deeplearning/tree/master/GAN).


## Poem Generator
A simple implement of chinese poem generator with LSTM.
<p align="center">
<img src="https://raw.githubusercontent.com/hjptriplebee/Chinese_poem_generator/master/demo2.png" width = "850" height = "350" alt="demo2" />
</p>

Please refer to [MC-PangHu](https://github.com/hjptriplebee/Chinese_poem_generator).


Updating.... 
Please help us to implement these examples, we need a simplified implementation. Or you have other nice examples, please add to this list.
