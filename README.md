# Off-Line-Signature-Verification

There are two ways to identify the signatures, off-line and on-line signature recognition. On-line signature assesses the parameters such as speed of writing, the force employed on the signing instrument, the position of the hand, etc., all of which are physical factors that are outside the scope of this project. Off-line signature verification essentially treats the signature as an image and uses Neural Networks to identify the validity of the signature. 

In a writer dependent model characteristics included are writer dependent threshold, features and classifiers. However, this simple image classifying neural network is not sufficient since a new neural network would have to be trained for each and every individual writer, which is highly inefficient and ineffective. 

The neural network proposed by the base paper (see references), is a Siamese Neural Network, i.e., a network which consists of twin convolutional networks accepting two distinct signature images that are either similar or dissimilar. This makes the neural network writer independent and requires a genuine signature to be passed along with the sample signature to determine its validity. 

This project implements both the methods to contrast their performances. 
