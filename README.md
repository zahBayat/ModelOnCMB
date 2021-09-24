# ModelOnCMB
Here is a prototype of a convolutional autoencoder that learns useful features of our training data, AKA the CMB_S4 patches, and tries to predict how they appear.
Our final model should be doing the same thing more efficiently and on the masked patches of a real map.

We used the simulation builder code for generating CMB maps and we created patches from them using the Data_Provider.
