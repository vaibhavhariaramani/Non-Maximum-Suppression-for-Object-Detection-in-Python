nms-python
==========

Python Implementation of Non-maximum suppression
## Description
Histogram of Oriented Gradients(HOG) combined with Support Vector Machines(SVM) have been pretty successful for detecting objects in images but the problem with those algorithms is that they detect multiple bounding boxes surrounding the objects in the image. Here’s where Non maximum suppression(NMS) comes to rescue to better refine the bounding boxes given by detectors. In this algorithm we propose additional penalties to produce more compact bounding boxes and thus become less sensitive to the threshold of NMS. The ideal solution for crowds under their pipelines with greedy NMS is to set a high threshold to preserve highly overlapped objects and predict very compact detection boxes for all instances to reduce false positives.
Non-Maximum Suppression for Object Detection in Python

## Test images
<center>
<img src="http://i.imgur.com/qKLZOT2.png" />
</center>

<div align=center><img src="https://github.com/bruceyang2012/nms_python/blob/master/images/Original_0.jpg">    <img src="https://github.com/bruceyang2012/nms_python/blob/master/images/After_NMS_0.jpg"/></div>
 
<div align=center><img src="https://github.com/bruceyang2012/nms_python/blob/master/images/Original_1.jpg">    <img src="https://github.com/bruceyang2012/nms_python/blob/master/images/After_NMS_1.jpg"/></div>

<div align=center><img src="https://github.com/bruceyang2012/nms_python/blob/master/images/Original_2.jpg">    <img src="https://github.com/bruceyang2012/nms_python/blob/master/images/After_NMS_2.jpg"/></div>

## References
1. [non-maximum-suppression-object-detection-python](https://sites.google.com/view/geeky-traveller/computer-vision/histogram-of-oriented-gradients-and-object-detection#h.p_KhiRYgfoJofc)
2. [https://github.com/vaibhavhariaramani/imutils](https://github.com/vaibhavhariaramani/imutils/object_detection.py)

# Resources 

To learn more about these Resources you can Refer to some of these articles written by Me:-

https://sites.google.com/view/geeky-traveller/computer-vision/histogram-of-oriented-gradients-and-object-detection

### Made with ❤️by Vaibhav Hariramani
#### About me

I am an Actions on Google, Internet of things, Alexa Skills, and Image processing developer.
I have a keen interest in Image processing and Andriod development.
I am Currently studying at  Chandigarh University, Punjab.

You can find me at:-
[Linkedin](https://www.linkedin.com/in/vaibhav-hariramani-087488186/) or [Github](https://github.com/vaibhavhariaramani) .

Happy coding ❤️ .
