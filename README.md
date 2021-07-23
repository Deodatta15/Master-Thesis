# Master-Thesis

The name of master thesis is 'Application of deep learning in the automated cutting of reinforcing textiles for parameter prediction and image classification.' The aim of the thesis is to reduce the waste material by increasing the reliability of the CNC machine and improve the quality control after the textiles are cut. 
The approach is to implement a machine-learning algorithm to predict the optimal parameters used in the cutting process and a deep learning algorithm to classify the images according to the quality of the cut.
A convolutional neural network and a Siamese neural network are trained to classify images into the classes namely ‘Good’ and ‘Bad’. A Convolutional Neural Network with pre-trained Efficientnet B0 network with a classification accuracy of 92% is implemented to classify the images of textiles according to their quality.
A Siamese Neural Network (SNN) is executed to investigate its performance on a small image dataset. The architecture using ResNet 50 pre-trained network achieved 100% classification accuracy.
Both the pre-trained Efficientnet B0 model and ResNet 50 model have been modified for the task of binary classification. 
