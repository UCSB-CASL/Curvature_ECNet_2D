# Error-correcting neural networks for two-dimensional curvature computation in the level-set method

### Contents

In addition to the usual `requirements.txt`, we include the following files under the corresponding resolution folder within `models/`:

1. `fdeep_k_nnet.json`: Neural network as exported by the `frugally-deep` library (without optimizer).
2. `k_nnet.h5`: Tensorflow/Keras model in HDF5 format (without optimizer).
3. `k_nnet.json`: Our custom JSON version of the neural network with hidden-layer weights encoded in `Base64` but decoded as `ASCII` text.  The "output" key refers to the last hidden layer.  It does not include the aditive neuron.
4. `k_pca_scaler.pkl`: PCA scaler stored in `pickle` format.
5. `k_pca_scaler.json`: JSON version of PCA scaler with plain-valued parameters.
6. `k_std_scaler.pkl`: Standard scaler in `pickle` format.
7. `k_std_scaler.json`: JSON version of standard scaler with plain-valued parameters.

### Contact

Please forward your questions to [this email](mailto:lal@cs.ucsb.edu).
