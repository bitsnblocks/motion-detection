#OpenCV C++ Motion Detection

**WARNING**

* **This repository is a proof of concept, and should not be used in production. The code in this project doesn't follow any good coding conventions.**
* **The core idea of this project has been integrated to [the Kerberos.io project](https://www.kerberos.io), which is a better reference to get started.**

This is a free, open source, motion detection project using OpenCV and C++. The project was orginally designed for [the Raspberry Pi](http://www.raspberrypi.org/). Due to the low CPU power and available memory, the algorithm of Collins et al. is used. More information about how it works can [be found here](http://blog.cedric.ws/opencv-simple-motion-detection).

The project includes 4 different parts:

* The source of the motion detection, using a simple rectangle where motion is detected.
* A commandline tool, selectregion, to select a region of interest on a selected image.
* The source of the motion detection, using a complex concave hull (this area is generated by the selectregion tool).
* A webinterface to view and filter the images in your webbrowser.

![motion detection](http://blog.cedric.ws/uploads/post/EYp61d1amMh9ZpXRkdmiRS64rdTaxx8pD6G9NdV4.png)
![select region](http://blog.cedric.ws/uploads/post/VAWTlWG8vwsRTP4LFqHgGpU8slTDWHalww7OzXlh.png)

#Installation 

Before you can use the motion detection, OpenCV must be installed on your device. You can [follow this link](http://blog.cedric.ws/install-opencv-on-raspberry-pi) for more information how to do it on the Raspberry Pi; there are a lot of other posts on the web which will you help either, so pick at random. After you installed OpenCV you can [follow this tutorial](http://blog.cedric.ws/raspberry-pi-opencv-create-a-security-system-web-interface).

#Selectregion tool

More information about the selectregion tool can be [found here](http://blog.cedric.ws/opencv-simple-motion-detection-concave-hull-optimization). The how to compile steps can be found there either.
