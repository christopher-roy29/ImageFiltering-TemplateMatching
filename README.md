# ImageFiltering-TemplateMatching
Two different tasks (Image Smoothing and Template Matching) are implemented in this project. The objective of first task is to perform image smoothing and image sharpening using a low-pass filter and a high-pass filter. The objective of second task is to match a template over a bigger image using normalized cross correlation metric.
The results of first task are stored in "./results/" and are named as \low-pass.jpg" and \high-pass.jpg". 

![image](https://user-images.githubusercontent.com/36618302/109545513-f17b3a00-7a96-11eb-934c-c0348a864770.png)

The low-pass filter (left) and the high-pass filter (right) used for the first task.

Second task is to locate a given image patch in a larger complete image. The logic for this task is written in a function named "\match" in "\task2.py", which takes a
complete image and a patch as inputs and returns the coordinates that the patch appears in the bigger image.
