# Title: Facial Expression Detection

# CS 663 Group 3 : Krina, Abinaya, Yunwei

# Goal: 
The identification of facial expressions that reveal human emotions. This project also helps identify non-verbal senior citizens’s emotions. 

# Section 1.1 INPUT

Two dimensional Images with multiple facial expressions under good lighting. 

# Section 1.2 OUTPUT

The output will be labeled as classification of 7 expressions, such as anger, sadness, happiness, fear, neutral, disgust, and surprised.

# Section 2: 

Minimum API 19, Android 4.4.2, using OpenCV version 2.4.10 in AndroidStudio and will test on Samsung Galaxy

# Section 3:

# Section 3.1: Overview: 

We have the following system components: 

1.	Image pre-processing 
2.	Feature extraction
3.	Classification

# Section 3.2: Image Pre-processing:
1.	Facial Detection 
2.	Cropping image to only the face area and eliminating unimportant areas
3.	Converting image to grayscale
4.	Removing noise using a Gaussian smoothing filter

# Section 3.3 Feature Extraction:
1.	Using edge detector on input
2.	Extract facial landmarks, such as, eyes, nose, mouth, jawline, eyebrows, using Adaboost algorithm 

# Section 3.4: CNN
1.	Minimum three layer convolutional neural network with n input and 7 output (7 facial expression classification)
2.	Training data using FER-2013 database. It contains training data with pre-labeled 7 classification in facial expression.

# Section 3.4 Reporting Results: 
	The App will show labeled images with classified facial expressions, such as anger, sadness, or surprised.

# Section 4 GUI Interface: 

2 interfaces:

1.	Initial interface that provides a button to start the application and capture image.

2.	The result interface that will show facial feature classification.

 
![image](https://github.com/CS663/Project-Proposal/blob/main/New%20Wireframe%201.png)
