EMOTION DETECTION USING IMAGE PROCESSING

A Brief Explaination About The Project:
In this project, user's emotion using its facial expressions will be detected. These expressions can be derived from the live feed via system's camera or any pre-exisiting image available in the memory. Emotions possessed by humans can be recognized and has a vast scope of study in the computer vision industry upon which several researches have already been done. The work has been implemented using Python (Open Source Computer Vision Library (OpenCV) and NumPy. The scanned image(testing dataset) is being compared to the training dataset and thus emotion is predicted. The objective of this project is to develop a system which can analyze the image and predict the expression of the person.


:WHAT IS IMAGE PROCESSING ?

Image processing is a method to perform some important operations on an image. In order to get an enhanced high quality image or to extract the most useful information from that.


:How Image Input Works In Computer?

Converts the image into an array of pixel values where the dimension of array depends on the resolution of the image


:This project is based on CNN,so what is CNN?

A feed forward network to process and recognize image data with the grid version.

![img7](https://user-images.githubusercontent.com/106025020/227607296-6f9eb3c2-5721-4665-93da-55c782ef1fd3.png)


LAYERS IN CNN:

First Layer: CONVOLUTIONAL LAYER

* First layer of CNN
* Stores the pixelated values of image into array
* Used for extracting the features of the image and reduce its dimensionality


Second Layer: Activation Function ReLu

* Converts negative values into zero
* ReLu is a half rectifier
   * f(y)=0 when y<0
   * f(y)=y when y>=0
   

Third Layer: POOLING LAYER

* Reduces the spatial size and numbers of parameters
* Helps to control overfitting
* Used to reduce dimensionality


Fourth Layer: Fully Connected Layer

*Combines all the fatures together to create a final model


![img6](https://user-images.githubusercontent.com/106025020/225396649-c738715d-399d-4c6e-8447-2f9771362e30.png)


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
