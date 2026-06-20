# scalable-ib-isit21
Code for our ISIT 2021 paper on scalable information bottleneck — multi-stage version of the IB method

# Scalable Vector Gaussian Information Bottleneck

Code for our paper at ISIT 2021.

[Paper (arXiv)](https://arxiv.org/abs/2102.07525)

## What this is

In the context of statistical learning, the Information Bottleneck (IB) can be used to seek a balance between accuracy and generalization capability through a suitable tradeoff between compression complexity, measured by minimum description length, and distortion evaluated under a logarithmic loss measure. This paper looks at a multi-stage version: instead of one description, the encoder produces several, each one adding more detail than the last. This is useful when we want different levels of accuracy depending on how much complexity (rate) we can afford.

We analyze the exact solution for the Gaussian case, and also give a neural-network version that works when you don't know the data distribution in advance, tested on MNIST.

## What's in this repo

- The variational/neural network version, trained and tested on MNIST

## Requirements

- Python 3.x
- TensorFlow
- numpy, matplotlib

## Citation

If you use this code, please cite:

\`\`\`bibtex
@inproceedings{mahvari2021scalable,
  title={Scalable Vector Gaussian Information Bottleneck},
  author={Mahvari, Mohammad Mahdi and Kobayashi, Mari and Zaidi, Abdellatif},
  booktitle={2021 IEEE International Symposium on Information Theory (ISIT)},
  year={2021}
}
\`\`\`
