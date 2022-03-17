# Image-Recognition-with-Neural-Network
In this study we will apply neural networks to recognize the images of handwritten numbers.

![front page](https://github.com/AgustinCarcelen/Image-Recognition-with-Neural-Network/blob/38d5f703b14a764e05fa0acfe0e985ee4c89df26/Images/Title_image.jpg)

## Table of content

- [Introduction](https://github.com/AgustinCarcelen/Image-Recognition-with-Neural-Network/blob/main/README.md#introduction)
- [Neural Network](https://github.com/AgustinCarcelen/Image-Recognition-with-Neural-Network/blob/main/README.md#neural-network)
- [Convolutional Network](https://github.com/AgustinCarcelen/Image-Recognition-with-Neural-Network/blob/main/README.md#convolutional-network)
- [Extra](https://github.com/AgustinCarcelen/Image-Recognition-with-Neural-Network/blob/main/README.md#extra)

## Introduction
Image recognition is a process executed by artificial intelligence software capable of recognizing images using complex mathematical algorithms. AI is capable of identifying, analyzing and comparing the bit arrays that make up a digital image, with the aim of carrying out some action based on the information obtained.<BR>
To show you how it works we have created two different networks. The first, simpler, only with neural networks and the second, more complex, with convolutional networks.<BR>
We have used the Mnist dataset, which is a database with 70,000 images of handwritten numbers. 60,000 are for training and 10,000 for validation.
  
## Neural Network
You can consult the notebook in the following [link](https://github.com/AgustinCarcelen/Image-Recognition-with-Neural-Network/blob/38d5f703b14a764e05fa0acfe0e985ee4c89df26/Code/Image%20Recognition%20with%20Neural%20Network.ipynb)<BR>
Our first network serves as an introduction and learning to neural networks. Here we only apply layers, the first for classification and the second for output.<BR>
Only with this we are able to obtain a 97% accuracy in our network.
![front page](https://github.com/AgustinCarcelen/Image-Recognition-with-Neural-Network/blob/38d5f703b14a764e05fa0acfe0e985ee4c89df26/Images/summary1.PNG)<BR>
  
## Convolutional Network
You can consult the notebook in the following [link](https://github.com/AgustinCarcelen/Image-Recognition-with-Neural-Network/blob/38d5f703b14a764e05fa0acfe0e985ee4c89df26/Code/Image%20Recognition%20with%20Convolutional%20Neural%20Network.ipynb)<BR>
A convolutional neural network is a type of artificial neural network where artificial neurons correspond to receptive fields in much the same way as neurons in the primary visual cortex of a biological brain.<BR>
Our second network is a bit more complex. For its assembly we have used two convolutional layers, two pooling layers, a preparation layer for the input data, a drop layer, a dense layer and an output layer. You have all the details of each one of them in the previous link.<BR>
This time we have achieved an accuracy of more than 99%
![front page](https://github.com/AgustinCarcelen/Image-Recognition-with-Neural-Network/blob/38d5f703b14a764e05fa0acfe0e985ee4c89df26/Images/Summary2.PNG)<BR>
  
## Extra
  - [Useful links](https://github.com/AgustinCarcelen/Image-Recognition-with-Neural-Network/tree/main/Useful%20links) -> Here you have several links with all the information collected to carry out these two networks<BR>
  - [Trello](https://trello.com/b/uc0wNm7h/image-recognition) -> Here you can find the process carried out day by day.<BR>
  - [Presentation](https://slides.com/agustincarcelenchicote/code-8ae58c) -> Here you can find the presentation of the project
