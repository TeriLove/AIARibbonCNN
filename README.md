## AIARibbonCNN
This repository contains the code to train and test a convolutional neural network which analyses 1600 angstrom AIA images. This code corrresponds to the paper [Analysing AIA Flare Observations using Convolutional Neural Networks](https://arxiv.org/abs/2005.13287).

The CNN is trained on AIA images containing Solar Flare observations. The network is trained using four classes as follows;
1. Quiet Sun
2. Two-Ribbon Flares
3. Limb Flares
4. Circular/Compact Ribbon Flares

The CNN itself is simple with only 2 convolutional layers implemented. The model was created to help analyse and locate flaring regions in observations with the eventual goal to create an automatic recognition process on incoming AIA data.

To see the training of the model (where k-fold validation is implemented) see `CNN_k_fold.ipynb`.
