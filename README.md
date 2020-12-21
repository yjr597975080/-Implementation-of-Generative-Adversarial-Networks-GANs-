# Implementation of Generative Adversarial Networks (GANs)

## Abstract

This is the final report of Advanced Statistical Machine Learning course presented
by authors. The report summarizes the generative adversarial networks (GANs).
The report describes: (1) What problem could GAN solve, (2) What are the concept
and cost function of GAN, (3) Architecture of our GAN with hidden layers, and
implementation on MNIST, SVHN and CelebA data, (4) Result of our GAN
model, (5) Implementations using WGAN Model on MNIST and SVHN data, (6)
Discussion of important takeaways and potential improvements.

## Introduction

Generative modeling is an unsupervised machine learning algorithm that could automatically learn
patterns of the input data and then generate new data points. This technique could solve the problem
when we want to train a classifier but do not have enough data. In some cases, we could create data
that improve classifier accuracy using generative models. Moverover, it is also useful for increasing
image resolution without introducing artifacts. However, given some high dimensional data such as
images or audio, understanding its probability distribution and generating samples following that
distribution are not trivial. Generative Adversarial Networks (GAN) provides a possible solution of
understanding the probability distribution of high dimensional data by constructing two networks, a
Generator G and a Discriminator D.

