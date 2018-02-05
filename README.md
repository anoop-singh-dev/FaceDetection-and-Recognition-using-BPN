# FaceDetection-and-Recognition-using-BPN

## Prerequisites
* Python 2.x
* OpenCV 3.x
* pillow python library

## Running the tests

### For Face Detection in image
* Go folder face_detection:- and run
* $ python face_detect.py a1.jpg haarcascade_frontalface_default.xml

![abc](https://user-images.githubusercontent.com/9657488/35817254-e79b3612-0ac2-11e8-9144-54cfbabedb03.png)

### For Face Detection through webcam
* $ python live.py haarcascade_frontalface_default.xml
### for face recognition

* run the dataSetGenerator.py and enter a unique id to create face samples with your face
* run trainer.py for trained dataset
* run detector.py for recognition the face
