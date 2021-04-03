# Face-detection-in-OpenCV

The code here detects face in images/ videos, crops the image to bounadry box of detected face and saves it. It can detect also multiplied faces in one image.
Face detection is a problem in computer vision of locating and localizing one or more faces in a photograph.


### Introduction
Locating a face in a photograph refers to finding the coordinate of the face in the image, whereas localization refers to demarcating the extent of the face, often via a bounding box around the face. Face detection is the first step in first recognition.

### Tools:
Python 3, OpenCV
OpenCV is included a deep learning-based face detector. The Caffe-based face detector can be found in the face_detector sub-directory of the <a href="https://github.com/opencv/opencv/tree/master/samples/dnn/face_detector">dnn</a> samples. It needs two files; the .prototxt file, which define the model architecture, and the .caffemodel file which contains the weights for the actual layers.

