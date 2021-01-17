# CV-Mask-detection
What would you do on a Sunday afternoon, if you could not go out due to a world pandemic?
No doubt for me, I'd code something!

My focus is on the world pandemic situation and Kaggle is a good place to find something interesting. I started <a href="https://www.kaggle.com/omkargurav/face-mask-dataset">here</a>.
I know, I know, "Wear a mask" could be a tricky one. As a result John is wearing the mask like a surgeon ready to cut and Carl thinks he's Batman. In order to prevent John to cut Carl, let's create something to help this guys.

This web application (built in Flask, TensorFlow and OpenCV) can be used to detect face masks in real-time videos or in images.
Let's see if Batman is wearing a mask.

## Test Detection
![Alt Text](https://github.com/pstndr/MaskDetection/blob/master/testDetection.GIF)

## Goal
The goal is to create a masks detection system, able to recognize face masks both in images, both in real-time video, drawing bounding box around faces. In order to do so, I finetuned MobilenetV2 pretrained on Imagenet, in conjunction with the OpenCV face detection algorithm: that allows me to turn a classifier model into an object detection system.

## Technologies
- Keras/Tensorflow
- OpenCV
- Flask
- MobilenetV2

## How to Run in 3 steps
1. Install the required packages:
```pip install -r requirements.txt```

2. In the command line (from the root folder):
```
python MaskDetector.py
```
3. Click on (or copy-paste) the link that appears on the prompt (tipically stuff like http://0.0.0.0:8080).

## Data
The dataset used for training the model is available <a href="https://www.kaggle.com/omkargurav/face-mask-dataset">here</a>.

