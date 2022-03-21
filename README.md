# Geometric Transformer for End-to-End Molecule Properties Prediction

An implementation of the Geometric Transformer described in ["Geometric Transformer for End-to-End Molecule Properties Prediction
" (IJCAI 2022)](https://arxiv.org/abs/2110.13721).

<p align="center">
<img src="https://user-images.githubusercontent.com/10303791/159278549-d00ab6ee-6e54-473e-b62a-8acdcd079253.PNG" alt="Geometric Transformer"
width="350px"></p>

## Abstract

Transformers have become methods of choice in many applications thanks to their ability to represent complex interaction between elements. 
However, extending the Transformer architecture to non-sequential data such as molecules and enabling its training on small datasets remain a challenge. 
In this work, we introduce a Transformer-based architecture for molecule property prediction, which is able to capture the geometry of the molecule. 
We modify the classical positional encoder by an initial encoding of the molecule geometry, as well as a learned gated self-attention mechanism. 
We further suggest an augmentation scheme for molecular data capable of avoiding the overfitting induced by the overparameterized architecture. 
The proposed framework outperforms the state-of-the-art methods while being based on pure machine learning solely, i.e. the method does not incorporate domain knowledge from quantum chemistry and does not use extended geometric inputs beside the pairwise atomic distances.


## Install
- Pytorch 1.13.1

## Script

## Reference
If you find this repo helpful, please consider citing:
    
## License
This repo is MIT licensed.
