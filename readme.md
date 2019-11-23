# Devanagiri Recognition 
This code helps you classify different alphabets of hindi language [Devanagari](https://en.wikipedia.org/wiki/Devanagari) Characters using convolutional network. 
<p align="center">
<img src="images/devanagari_generate.gif" title="Generated Data Animation" alt="Generated Data Animation">
</p>

### Code Requirements


•	Need some Pre-installed Packages like 
*1. Anaconda Distribution- Python 3.7
Link - https://www.anaconda.com/distribution/
*2. OpenCV – it should be installed via anaconda prompt after installation of Anaconda Distribution
Link - https://anaconda.org/conda-forge/opencv
*3.	WebCam 

You can install Conda for python which resolves all the dependencies for machine learning. This code is checked on :
```
Python version = 3.5.6
keras version = 2.2.0
Tensorflow version = 1.10.0

```


### Description
This code successfully recognizes hindi characters.

### Technique Used

I have used convolutional neural networks.
I am using Tensorflow as the framework and Keras API for providing a high level of abstraction.

### Architecture

#### CONV2D --> MAXPOOL --> CONV2D --> MAXPOOL -->FC -->Softmax--> Classification

### Some additional points

1) You can go for additional conv layers.
2) Add regularization to prevent overfitting.
3) You can add additional images to the training set for increasing the accuracy.


### Python  Implementation

1) Dataset- DHCD (Devnagari Character Dataset) [data.csv](https://drive.google.com/open?id=1YLL4gAWg6W_L9NNPSMhsv8J6Rq_lNWbI)
2) Images of size 32 X 32
4) Convolutional Network Support added.

### Train Accuracy ~ 94%
### Test Accuracy ~ 93%

### Execution for writing through webcam
<img src="https://github.com/Priyanshuuu/Hindi-Alphabets-Recognition/blob/master/images/sample_video.gif">
To run the code, type `python app.py`

```
python app.py
```





