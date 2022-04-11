# Object-tracking
Object tracking is a computer vision task that refers to the process of finding and tracking the position of a predefined object that is moving in the frames of a video.
Videos can be treated as stack of pictures called frames. Here we are comparing different frames(pictures) to the first frame which should be static(No movements initially). We compare two images by comparing the intensity value of each pixels.the differences founded in the two frames help us to find the movement of specific portion in video.
Here we are using OpenCV module as it is providing various inbuild function for object tracking such as backprojection,histogram , camshift and many more.
Here we are converting colour of each frame to hsv because HSV is more robust towards external lighting changes. This means that in cases of minor changes in external lighting (such as pale shadows,etc. ) Hue values vary relatively lesser than RGB values.
