EMOTION DETECTION USING IMAGE PROCESSING

A Brief Explaination About The Project: In this project, user's emotion using its facial expressions will be detected. These expressions can be derived from the live feed via system's camera or any pre-exisiting image available in the memory. Emotions possessed by humans can be recognized and has a vast scope of study in the computer vision industry upon which several researches have already been done. The work has been implemented using Python (Open Source Computer Vision Library (OpenCV) and NumPy. The scanned image(testing dataset) is being compared to the training dataset and thus emotion is predicted. The objective of this project is to develop a system which can analyze the image and predict the expression of the person.

:WHAT IS IMAGE PROCESSING ?

Image processing is a method to perform some important operations on an image. In order to get an enhanced high quality image or to extract the most useful information from that.

:How Image Input Works In Computer?

Converts the image into an array of pixel values where the dimension of array depends on the resolution of the image

:This project is based on CNN,so what is CNN?

A feed forward network to process and recognize image data with the grid version.

![img7](https://user-images.githubusercontent.com/106025020/229363533-eb9c01ae-ff57-438f-9508-7b9931199579.png)


LAYERS IN CNN:

First Layer: CONVOLUTIONAL LAYER

First layer of CNN
Stores the pixelated values of image into array
Used for extracting the features of the image and reduce its dimensionality
Second Layer: Activation Function ReLu

Converts negative values into zero
ReLu is a half rectifier
f(y)=0 when y<0
f(y)=y when y>=0
Third Layer: POOLING LAYER

Reduces the spatial size and numbers of parameters
Helps to control overfitting
Used to reduce dimensionality
Fourth Layer: Fully Connected Layer

*Combines all the fatures together to create a final model

![img6](https://user-images.githubusercontent.com/106025020/229363555-3d53df18-b75e-4e16-a785-d4efc945ae50.png)


Packages need to be installed:-

->pip install numpy

->pip install opencv-python

->pip install keras

->pip3 install --upgrade tensorflow

->pip install pillow

download FER2013 dataset:-

->from below link and put in data folder under your project directory

https://www.kaggle.com/msambare/fer2013

Run Your Emotion Detection Test File:-

python TestEmotionDetector.py


HEART RATE DETECTION USING IMAGE PROCESSING:


INTRODUCTION

A person’s heart rate can be indicative of their health, fitness, activity level, stress, and much more. Cardiac pulse is typically measured in clinical settings using electrocardio-gram (ECG), which requires patients to wear chest straps with adhesive gel patches that can be abrasive and become uncomfortable for the user.Heart rate may also be monitored using pulse oximetry sensors that may be worn on the fingertip or earlobe. These sensors are not convenient for longterm wear and the pressure can become uncomfortable over time. In addition to the discomforts of traditional pulse measurement devices, these devices can damage the fragile skin of premature new-borns or elderly people. For these populations especially, a non-contact means of detecting pulse could be very beneficial. Non-contact heart rate measurement through a simple webcam or phone camera would also aid telemedicine and allow the average person to track their heart rate without purchasing special equipm


DIFFERENT STEPS IN THE PROJECT

The proposed method includes the following steps: (1) The facial video is recorded with a standard RGB camera, and the facial and background ROI signals are extracted from each video frame. (2) The JBSS method is used to remove the common illumination component from the facial and background ROI signals, obtaining a new facial ROI signal. (3) The pulse signal is extracted from the new facial ROI signal using the projection method. (4) The green channel signal from the facial ROI is used to identify the pulse signal, and the HR is calculated using the fast Fourier transform (FFT).The highest peak is the Heart rate.The colours are then amplified to make the color variation visible.

DEMO SHOTS

![result](https://user-images.githubusercontent.com/106025020/229366976-4888d229-34f0-4d49-8abf-1a8fa7b6aa0e.png)


Packages need to be installed

->scipy

->dlib

->imutils

->numpy

->opencv-python

->PyQt5

->pyqtgraph

TO IMPLEMENT THE CODE:
python GUI.py


REFERENCE:

:-Emotion & Heartbeat Detection using Image
Processing
Kaushal Kanakia, Saurabh Patil, Sujay Sabnis, Vedant Shah


