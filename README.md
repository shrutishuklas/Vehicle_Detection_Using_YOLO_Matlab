# Vehicle_Detection_Using_YOLO_Matlab


## Description:
  This repository has been created as part of Final Project of COT5930: Digital Image Processing.
  Here, we have implemeted pretrained YOLO v2 for vechicle detection in MATLAB. 
  
  Contributors : Shruti Shukla, Georgios I. Orfanidis and Gabriel Gilman.
  
 ## Overview
  You Only Look Once is known by the acronym YOLO. This algorithm (which operates in real-time) can find and identify different items in images. The class probabilities of the discovered photos are provided by the object identification process in YOLO, which is carried out as a regression problem.The pretrained networks are trained to detect vechicles from several images. 
  
## Requirement
   + MATLAB R2020a or later
   + Deep Learning Toolbox
   + Computer Vision Toolbox

## YOLO v2 Algorithm Details
YOLO architecture resembles GoogleNet. It has overall 24 convolutional layers, four max-pooling layers, and two fully.
The architecture of YOLO functions by scaling down the input image to 448x448 before entering the convolutional network. A 3x3 convolution is used to create a cuboidal output, in succession of a 1x1 convolution which ensures the reduction of the number of channels. The final layer utilizes a linear activation function while ReLU is the activation function used in the background.
The model is further regularized and prevented from overfitting using additional techniques like batch normalization and dropout.

![plot]()
