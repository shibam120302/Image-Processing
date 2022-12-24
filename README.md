# Image Processing By-Shibam Nath
![ip](https://miro.medium.com/max/720/1*VeUwoUU7wb2T-NDciUuo7w.webp)

## Introduction
Image Processing and Machine Learning, the two hot cakes of tech world. Did you know that we are the most documented generation in history of humanity. Every minute a whooping 1.78 million GB data gets produced online !!!. That’s a lot of data and a big chunk that of data is images and videos. This is where automated image processing and machine learning comes in.
There never has been an more awesome time to be a geek. Plethora of avenues are opening up for those with skills in Machine learning in general and image processing in particular.

After we are done with the tutorial, you would be able to pass an input image to our program and our program should be able to count the number of peoples appearing in that image. Additionally we would also be creating an bounding box around each of the detected person.

## Prerequisites
This post of mine is an humble effort to get people interested in this area and by using a simple example, demonstrate how easy is it to get started. All we need would be a working knowledge of Python and a little background of OpenCV.

Python — Although there are multiple tutorials available online, personally, I found dataquest.io to be an wonderful python learning platform, for beginners and experienced alike.
OpenCV — Same as python, OpenCV also has a lot of online tutorials. One site that I find myself referring to again and again is the official documentation.
HaaR Cascades — OpenCV exposes special methods to train our own custom algorithms to detect any object of interest in an input image. HaaR cascade are those files that contain that trained model
I realize that a lot of folks might already have a good knowledge of python but might still be just starting out with OpenCV. Hence for the sake of completeness, I have included the next section with a little background on OpenCV and HaaR Cascade files. Please feel free to skip it, if needed.

### First thing first, What be, OpenCV and Haar Cascade?
OpenCV or Open Source Computer Vision Library is an open source computer vision and machine learning library. Although most popular with python, it interfaces quite well with C++, Java and MATLAB. OpenCV is native written in C++ and is widely used with computer vision related applications running on variety of systems like Windows, Linux, Android, Mac OS etc. This multi language/OS support makes is specially useful in variety of IoT applications.

OpenCV uses HaaR cascade files for object detection. HaaR cascade files are nothing but models trained by OpenCV to detect an object of interest in input images. You can create a HaaR cascade file for any real world object. All you would need is a lot of positive samples images containing the object and a lot of negative sample images, containing everything but the object. Next using using methods exposed by OpenCV, we can run training cycle to generate our own HaaR classifier or an HaaR Cascade file. For this tutorial however, we would be using one of the classifiers publicly available from OpenCV. This classifier specializes in detecting a person in an image. In future tutorials we will touch briefly on how to create your own classifier and then run object detection using that.
