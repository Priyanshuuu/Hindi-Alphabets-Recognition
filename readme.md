# Devanagiri Recognition 
This code helps you classify different alphabets of hindi language (Devanagiri) using Convnets
<p align="center">
<img src="https://github.com/Natsu6767/Generating-Devanagari-Using-DRAW/blob/master/images/devanagari_generate.gif" title="Generated Data Animation" alt="Generated Data Animation">
</p>

### Code Requirements
You can install Conda for python which resolves all the dependencies for machine learning.

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

### Train Acuracy ~ 95%
### Test Acuracy ~ 92%

### Execution for writing through webcam
To run the code, type `python app.py`

```
python app.py
```





