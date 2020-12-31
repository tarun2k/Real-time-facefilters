# Face Filters on Real-Time Images
A machine learning project to detect human faces in real-time images and track the movement of the fist to apply various filters on the face (namely: hat, sunglasses, and mustache).
In this project, we created a Convolution Neural Network (CNN) to detect facial landmarks and trained the model on 300W (300 faces in the wild) dataset. 

The following are the 68 facial landmarks predicted on an image of mine: 

![alt text](https://github.com/tarun2k/Real-time-facefilters/blob/master/results/facial_landmarks.JPG?raw=true)

Using OpenCV library, we tracked the movement of the fist in real-time images and change filters on the face detected using OpenCV Cascade Classifier where haarcascade_frontalface_default.xml is a pre-trained classifier XML file. 

The following are the results achieved:

<b> Sunglasses </b>

![alt text](https://github.com/tarun2k/Real-time-facefilters/blob/master/results/sunglasses.JPG?raw=true)

<b> Hat </b>

![alt text](https://github.com/tarun2k/Real-time-facefilters/blob/master/results/hat.JPG?raw=true)

<b> Moustache </b>

![alt text](https://github.com/tarun2k/Real-time-facefilters/blob/master/results/moustache.JPG?raw=true)

<hr> 

<h3> Programming Language used: Python </h3>
<h3> Platform used: Jupyter Notebooks, Kaggle </h3>
