# CheMixNet
CheMixNet is a general-purpose neural network that combines two neural architectures (illustrated below). 
The first neural architecture is a fully connected multi-layer perceptron network trained on molecular fingerprints. 
The second neural architecture have 3 flavors: 
1. CNN
2. RNN (LSTM or GRU)
3. CNN-RNN (CNN followed by LSTM or GRU)

<p align="center">
  <img src="images/chemixnet.png" width="600">
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
