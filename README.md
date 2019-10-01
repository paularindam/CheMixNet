# CheMixNet
CheMixNet is a general-purpose neural network that combines two neural architectures (illustrated below). 
The first neural architecture is a fully connected multi-layer perceptron network trained on molecular fingerprints. 
The second neural architecture is trained on SMILES sequences and have 3 choices for their neural architecture: 
1. CNN
2. RNN (LSTM or GRU)
3. CNN-RNN (CNN followed by LSTM or GRU)

<p align="center">
  <img src="images/model.png" width="600">
</p>

The proposed architecture performs better than other state of the art architectures such as SMILES2vec, Chemception, ConvGraph etc. 

Requirements: 
1. Keras 2.0 or higher
2. Tensorflow 1.7 
3. RDKit 2017.09.1
4. Scikit-Learn 0.19.1
5. Numpy 1.14
6. Pandas 0.22
7. DeepChem 2.1 (for benchmarking against convolutional graph networks) 

## Developer Team

The code was developed by <a href="http://www.arindampaul.me/">Arindam Paul</a> by the <a href="http://cucis.ece.northwestern.edu/">CUCIS</a> group at the Electrical and Computer Engineering Department at Northwestern University. 


## Citation
If you use this code or data, please cite:

Arindam Paul, Dipendra Jha, Reda Al-Bahrani, Wei-keng Liao, Alok Choudhary, Ankit Agrawal. CheMixNet: Mixed DNN Architectures for Predicting Chemical Properties using Multiple Molecular Representations. Thirty-second Conference on Neural Information Processing Systems (NIPS), 2018, DOI:  https://arxiv.org/abs/1811.08283


## Questions/Comments:

email: apaul@u.northwestern.edu

Copyright (C) 2019, Northwestern University.

See COPYRIGHT notice in top-level directory.

## Funding Support

This work was performed under the following financial assistance award 70NANB19H005 from U.S. Department of Commerce, National Institute of Standards and Technology as part of the Center for Hierarchical Materials Design (CHiMaD). Partial support is also acknowledged from DOE awards DE-SC0014330, DE-SC0019358.
