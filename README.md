# Collaborative Variational Autoencoder
This code is associated with the following paper:

Xiaopeng Li and James She. Collaborative Variational Autoencoder for Recommder Systems. ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 2017 (KDD'17).

### Prerequisities
* The code is written in Python 2.7. 
* To run this code you need to have TensorFlow installed. The code is tested with TensorFlow 0.12.1.

### Usage
The program consists of two parts: pre-train in VAE manner and finetuning in CVAE manner. The core code files are in lib/ directory and the test code files are test_vae.py and test_cvae.py. To run the program, you should first run test_vae.py to pre-train the weights of inference network and generation network. The pre-trained weights will be saved under model/ directory. Then test_cvae.py can be run for the CVAE model. And the model will be saved also under model/ directory.