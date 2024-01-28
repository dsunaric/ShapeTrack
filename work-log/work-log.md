# Work log
work log / notebook for this Project. 

## Idea: OpenCV for video analysis 
OpenCV seems to have a good API for Editing videos and fetures for object detetion.
see: https://github.com/liliumbosniacum/shape-detection/blob/master/src/main/java/com/lilium/shapedetection/ShapeDetection.java

## idea: Wrap Video frames in CodeDraw Images 

Issue: see if this has good enough performance 
I started with etracting frames using OpenCV videCapture and see how drawing frames in realtime works with codedraw.

This works great with using the own camera as input and is currently a bit delayed when i try to use a saved mp4 file, 
I need to dive depeer to find the bottleneck with the saved mp4 file