# S6
Assignment 6


##Create NN Class and specify the required Layers. The Class takes Batchnorm Type as Parameter. There are two possible values, GBN or BN. By default class is intantiated with BN = Batch Normalization

## Train and Test Functions are created. The Test function spits out/retuens the list of Images falsly classified.

##Additionally The Train and Test functions's Loss and Accuracies are stored in below declared Lists. These lists shall be used to generate graph.

## exec_Models Function: This  Function will be called by Main Iterator to execute/call Models for 8 different combination of Regualarization and Batch normalization

## Load_data: Function to load data from Dataset, and split into Train/Test, normalize and also Batch size is defined here

##Iterate through the two Options, With BN and With GBN and call the model for all 4 options - with/without L1,L2, with L1, with L2

## Consider Two cases BN & GBN: For both type of Normalizations, consider cases without Regularization and display 25 images out of these sets
