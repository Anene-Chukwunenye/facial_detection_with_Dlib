# Facial_detection_with_Dlib

### Facial feature detection using Dlib

#### The face detection algorithm  is in Python with the use of Dlib. The two face detection models used are:
1. Histogram of Oriented Gradients using Dlib (HOG)
2. Convolutional Neural Networks using Dlib (MMOD)

##### Histogram of Oriented Gradients (HOG) in Dlib: The idea behind HOG is to extract features into a vector, and feed it into a classification algorithm like a Support Vector Machine for example that will assess whether a face (or any object you train it to recognize actually) is present in a region or not.

##### MMOD Convolutional Neural Network in Dlib: It uses a Maximum-Margin Object Detector(MMOD) with CNN based features. The training process for this method is very simple and you don’t need a large amount of data to train a custom object detector. The pre-trained model can be downloaded from the dlib-models repository (https://github.com/davisking/dlib-models).


#### A very small dataset was used to check how well the models could detect faces. However there are some setbacks with Dlib as it can not accurately detect small sized faces
