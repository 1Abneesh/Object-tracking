# Object Tracking Project

## Introduction

Object tracking is a computer vision task that refers to the process of finding and tracking the position of a predefined object that is moving in the frames of a video. Videos can be treated as a stack of pictures called frames. Here we are comparing different frames (pictures) to the first frame which should be static (No movements initially). We compare two images by comparing the intensity value of each pixel. The differences found in the two frames help us to find the movement of a specific portion in the video. 

## Methodology

Here, we are using OpenCV module as it provides various inbuilt functions for object tracking such as backprojection, histogram, camshift, and many more. Here, we are converting the color of each frame to HSV because HSV is more robust towards external lighting changes. This means that in cases of minor changes in external lighting (such as pale shadows, etc.), hue values vary relatively lesser than RGB values.

## Key Tools Used
- OpenCV

## Conclusion

Object tracking is an important aspect of computer vision as it finds numerous applications in various fields such as security and surveillance, robotics, and many more. By using OpenCV, we can easily track an object in a video and process the information to get desired results.

