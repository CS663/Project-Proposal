# Title: Facial Expression Detection

# CS 663 Group 3 : Krina, Abinaya, Yunwei

# Goal: 
In order to assist visually impaired people this project is introduced to identify the expression or emotion of the confronting person and hence enable a better communication. 

# Section 1.1 INPUT

Two dimensional Images of peoples with multiple facial expressions under good lighting. 

# Section 1.2 OUTPUT

The output will be labeled as classification of 7 expressions, such as anger, sadness, happiness, fear, neutral, disgust, and surprised. The identifies expression will be conveyed to the person as audio.

# Section 2: 

Minimum API 19, Android 4.4.2, using OpenCV version 2.4.10 in AndroidStudio and will test on Samsung Galaxy

# Section 3:

# Section 3.1: Overview: 

We have the following system components: 

1.	Image pre-processing 
2.	Face Detection
3.	Classification
4.	Text to Speech Conversion

# Section 3.2: Image Pre-processing:
1.	Cropping image to only the face area and eliminating unimportant areas
2.	Converting image to grayscale
3.	Removing noise using a Gaussian smoothing filter

#Section 3.3: Face Detection:
	Object Detection using Haar feature-based cascade classifiers is an effective object detection method proposed by Paul Viola and Michael Jones in their paper, "Rapid Object Detection using a Boosted Cascade of Simple Features" in 2001. It is a machine learning based approach where a cascade function is trained from a lot of positive and negative images. It is then used to detect objects in other images. Here we will work with face detection. Initially, the algorithm needs a lot of positive images (images of faces) and negative images (images without faces) to train the classifier.

# Section 3.4: CNN
1.	Faces detected from above step is fed into CNN to identify emotions.
2.	Minimum three layer convolutional neural network with n input and 7 output (7 facial expression classification)
3.	Training data using FER-2013 database. The Fer2013 dataset from kaggle has more than 30,000 images covering almost all the facial expressions of humans. It contains training data with pre-labeled 7 classification in facial expression.

![image](https://github.com/CS663/Project-Proposal/blob/main/emotionDetection.png)

# Section 3.4 Reporting Results: 
	The App will show labeled images with classified facial expressions, such as anger, sadness, or surprised.

# Section 4 GUI Interface: 

2 interfaces:

1.	Initial interface that provides a button to start the application and capture image.

2.	The result interface that will show facial feature classification.

 
![image](https://github.com/CS663/Project-Proposal/blob/main/New%20Wireframe%201.png)
