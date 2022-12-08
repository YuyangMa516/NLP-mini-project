# NLP-mini-project
NLP mini project


Unit Title: Natural Language Processing for the Creative Industries
Project Proposal
Name： YUYANG MA
ID：22040677



Introduction

Hi, this is Yuyang Ma from Modular. 
My ID is 22040677. 
I wasn't able to successfully do the project in the Example projects, so I chose a project that I had come across before and was related to this topic, a CNN-based project for 10 types of object recognition. For colorful images, it is more efficient to use CNN. In this project, I used the Cifar 10 dataset.
I actually write my comments, broad framework and logic, and ideas in my code. Please refer to my code for more details. I think that fits the description better.



Description

Here is my logical framework.
 1.	    Import the data, import the Three Musketeers and Tensorflow;
 2.	    Load the dataset cifar 10, for training and calibration data, receiving and splitting data
 3.	    Split the data and take 5,000 as check data, same with x&y
 4.	    Check the shape
 5.	    Draw one for checking, and add a title
 6.	    Do a pre-processing of the data set
 7.	    Normalize the data to narrow down the range, into a floating point shape, two-dimensional, reduced, receive
 8.	    Defining Convolutional Neural Networks. ( (1) 2 convolutions, one pooling, three repetitions (2) Flattening (3) Fully connected )
 9.	    Configuring the network
 10.	   Training model
 11.	   Watch the data trend， draw a picture
 12.	   Network optimization, output charts((1)	Add dropout to reduce overfitting.(2)	2 convolutions, one pooling, three repetitions, total 3 layers of operations (3)	Flattening (4)	Fully connected
   
   
   
Conclusion

👉👉👉👉Training data is 83.9% and calibration data is 70.6%👈👈👈👈👈👈 <br>
After adding dropout to reduce overfitting <br>
👉👉👉👉Training data is 87.2% and calibration data is 79.7%👈👈👈👈👈👈

