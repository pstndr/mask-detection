# CV-Mask-detection
What would you do on a Sunday afternoon, if you could not go out due to a world pandemic?
No doubt for me, I'd code something!
My focus is on the world pandemic situation, so why not to code something related?
I know, I know, "Wear a mask" could be a tricky one. As a result John is wearing the mask like a surgeon ready to cut and Carl thinks he's Batman. In order to prevent John to cut Carl, let's create something to help this guys.

This web application (built in Flask, TensorFlow and OpenCV) can be used to detect face masks in real-time videos or in images.
Let's see if Batman is wearing a mask.

## Demo
![Alt Text](https://github.com/GalileoParise/CV-Mask-detection/blob/master/mask_detection_live.gif)

## Goal
The goal is to create a masks detection system, able to recognize face masks both in images, both in real-time video, drawing bounding box around faces. In order to do so, I finetuned MobilenetV2 pretrained on Imagenet, in conjunction with the OpenCV face detection algorithm: that allows me to turn a classifier model into an object detection system.

## Technologies
- Keras/Tensorflow
- OpenCV
- Flask
- MobilenetV2

## Usage
You have to install the required packages, you can do it:
- via pip
```pip install -r requirements.txt```
- or via conda
```conda env create -f environment.yml```

Once you installed all the required packages you can type in the command line from the root folder:

```
python wsgi.py
```
and click on the link that the you will see on the prompt.

## Data
The dataset used for training the model is available <a href="https://www.kaggle.com/omkargurav/face-mask-dataset">here</a>.

