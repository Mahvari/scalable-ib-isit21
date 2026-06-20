# Scalable Vector Gaussian Information Bottleneck

Code for our paper at ISIT 2021.

[Paper (arXiv)](https://arxiv.org/abs/2102.07525)

## Abstract

In the context of statistical learning, the Information Bottleneck (IB) can be used to balance accuracy and generalization by optimizing a suitable tradeoff between compression complexity, measured by minimum description length, and distortion under a logarithmic loss measure. This paper considers a multi-stage version: instead of one description, the encoder produces several, each one adding more detail than the last. This is useful when we want different levels of accuracy depending on complexity (rate) we can afford.

We analyze the exact solution for the Gaussian case and also provide a neural network version that works when you don't know the data distribution in advance, tested on MNIST.

## What is in this repository

- The variational/neural network version, trained and tested on MNIST

## Setup

- Python
- TensorFlow

## Citation

```bibtex
@inproceedings{mahvari2021scalable,
  title={Scalable Vector Gaussian Information Bottleneck},
  author={Mahvari, Mohammad Mahdi and Kobayashi, Mari and Zaidi, Abdellatif},
  booktitle={2021 IEEE International Symposium on Information Theory (ISIT)},
  year={2021}
}
```

