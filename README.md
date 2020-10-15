# XRD-NN

## Description

A simple NN-approach to facilitate the identification of complex multiphasic thin-film compounds from powder XRD-pattern in the Al-O-Sr-Li composition pool. 

The training data is composed of simulated XRD-patterns from a class of 29 possible compounds by combintorically mixing the patterns into binary and ternary systems. The data is further augmented by taking into account the intricacies of thin film deposition such as peak shifts due to residual stresses, peak scaling, as well as peak elimination as a consequence of preferred crystallographic orientations during growth.

The trained model correctly predicts the presence of the constituent phases from the XRD-patterns of the unary, binary and ternary mixtures with an average validation accuracy of around 60%. 

The XRD-patterns are simulated with the pymatgen package from Crystallgraphic information files which are freely available on the Crystallography Open Database.

The model is designed using the Tensorflow/Keras framework and trained on Google Colab.


## Context
This is just a hands-on learning project I did in order to get familiar with keras and tensorflow.
By no means do I claim to provide the proper network-architecture or even the appropriate way of input-data preparation and augmentation. I'm pretty sure this can be accomplished in a better way. 

However, I do believe that this still might be useful as starting point for other machine learning novices because chemical compound identification from XRD-patterns is an interesting real-life problem and using this project you can skip the labrious and sometimes boring phase of data-mining.
