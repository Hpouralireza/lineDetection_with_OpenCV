# lineDetection_with_OpenCV

### Find the road line in two ways:
#### 1- threshold & findContours
#### 2- erode method

#
First of all, we read the image and perform some steps on it, such as Gaussian/median Blur and Grayscale conversion.
#

For the first method, we use Binary threshold and then after finding the Contours, we draw them.

![Threshold method](https://github.com/Hpouralireza/lineDetection_with_OpenCV/assets/47522202/4cff5361-ec66-4b95-be17-ecdb9627d2ab)

#

And in the second method, after defining a simple kernel, we use the Erode

![Erode method](https://github.com/Hpouralireza/lineDetection_with_OpenCV/assets/47522202/c6710163-0afd-4c08-9af9-f2a00bfcbae6)
