# Real-Time Sign Language Gesture Recognition

The aim of this project is to recognise American Sign Language (ASL) in real time using the webcam. It is developed in python 3.8.3 using TensorFlow, OpenCV. InceptionV3 model is used, whoch is a Convolutional Neural Network (CNN) model for classification.


## Requirementss

Numpy:          1.18.5 
Matplotlib:     3.2.1
Tensorflow:     2.2.0
OpenCV-Python:  4.2.0.34

See requirements.txt for complete list of packages and its version.

###Install using PIP
```
pip install -r requirements.txt
```

## Execution
### Training
```
python train.py
```

### Classafying Single Image
```
python classify.py path/to/image.jpg
```

### Real-Time Classification
```
python classify_webcam.py
```
Keep your hand inside the rectangle.
