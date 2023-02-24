# Deep Capsule Encoder-Decoder Network for Surrogate Modeling and Uncertainty Quantification

This repository contains the code and data for the article "Deep Capsule Encoder-Decoder Network for Surrogate Modeling and Uncertainty Quantification" by Akshay Thakur and Souvik Chakraborty.

## Abstract

In this article, we propose a deep learning model for surrogate modeling and uncertainty quantification using capsule networks. 
The proposed model, called deep capsule encoder-decoder network (DCEDN), is a variant of the capsule network architecture that combines the benefits of both encoder-decoder networks and capsules. 
The DCEDN is trained to learn a low-dimensional representation of high-dimensional inputs, which can then be used for surrogate modeling and uncertainty quantification tasks. 
We evaluate the performance of the DCEDN on two different applications: a fluid dynamics problem and a materials science problem. 
The results show that the DCEDN outperforms several state-of-the-art models in terms of accuracy, efficiency, and robustness.

## Contents

- `Model and Experiments`: The two jupyter notebooks contain the model and the scripts to run the experiments and reproduce the results reported in the article.

##Data
The code for data generation for SPDE is based on code provided with [1](https://doi.org/10.1016/j.jcp.2018.08.036),
and the data for pressure Poisson equation is taken from article [2][https://doi.org/10.1016/j.neunet.2021.11.022]. 

## Requirements

The code is written in Python 3 and requires the following libraries:

- Tensorflow 2.9.2
- Pandas
- Numpy
- Matplotlib

If you use the code or data in this repository for your research, please cite the following article:

