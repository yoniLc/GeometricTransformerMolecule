# Geometric Transformer for End-to-End Molecule Properties Prediction

An implementation of the Geometric Transformer described in ["Geometric Transformer for End-to-End Molecule Properties Prediction
" (IJCAI 2022)](https://arxiv.org/abs/1909.09036).


<p align="center">
<img src="./transformer_image_3.PNG" alt="Geometric Transformer"
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
- Python3 (Recommend Anaconda)
- `pip install -r requirements.txt`

## Results reproduction
To reproduce the performance of the main model in our paper for BCH(63,51):

1. Run `python main.py`
2. Training with GPU. For 3 days of training with V100 32GB GPU. At epoch ±316 you should get this BER results:

## Reference
If you find this repo helpful, please consider citing:
    
## License
This repo is MIT licensed.
