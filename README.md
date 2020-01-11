# Face-recognition
Face Detection with OpenCV


Here we want to Make a face recognition with OpenCV which is one of the most classic problems in computer vision and we 
are going to proceed as follow:

-First of all, the main library we are going to use here is opencv library that's why we import cv2.

-The next we load cascade for the face and eyes and We write a function that takes as input the image in black and white (gray) 
and the original image (frame), and that will return the same image with the detector rectangles.

-If our frame contains one or several mages, we will use detectMultiScale method to locate them and for each detected 
face we paint a rectangle around the face in Bleu and the eyes in Green for the output which the same as the input but 
this time having the colored frames around indicating the face and eyes.

-We want to capture with the webcam infinitely until break so that as long as the camera observes, it tries to detect until we stop.

