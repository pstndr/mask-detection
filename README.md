# Mask Detector
What would you do on a Sunday afternoon, if you could not go out due to a world pandemic?
No doubt for me, I'd code something!

My focus is on the world pandemic situation and Kaggle is a good place to find something interesting. I started <a href="https://www.kaggle.com/omkargurav/face-mask-dataset">here</a>.

I know, I know, "Wear a mask" could be a tricky one. As a result John is wearing the mask like a surgeon ready to cut and Carl thinks he's Batman. In order to prevent John to cut Carl, let's create something to help this guys.

This web application (built in Flask, TensorFlow and OpenCV) can be used to detect face masks in real-time videos or in images.
Let's see if Batman is wearing a mask.

## Idea
Practically, as a result, with a bit of copy and paste from Stackoverflow (a little <a href="https://ih1.redbubble.net/image.1702670242.6307/pp,840x830-pad,1000x1000,f8f8f8.jpg">tribute</a>) I managed to build a web-app capable to recognize if you're wearing a mask or not. It does not have some flaws, but lots and lots of them.

## Test Detection
![Alt Text](https://github.com/pstndr/MaskDetection/blob/master/testDetection.GIF)


## How to Run in 3 steps
1. Install the required packages:
```pip install -r requirements.txt```

2. In the command line (from the root folder):
```
python MaskDetector.py
```
3. Click on (or copy-paste) the link that appears on the prompt (tipically stuff like http://0.0.0.0:8080).

## Development
I'm thinking about developing a more complex tool, capable of recognizing if you're wearing the mask properly or not, but it takes me a bit of time. Maybe next Sunday.

## Enjoy