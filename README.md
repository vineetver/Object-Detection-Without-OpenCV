# Object Detection without OpenCV

This notebook demonstrates multidimensional motif search in python.

In this notebook we consider a simple case:

* We have a image of chickens
* Inside image of chickens theres a bug
* We want to find the coordinates of the bug

This notebook does not use any image detection or pattern matching algorithms/libraries. OpenCV is only used for I/O.

### Example

For the input image below, in which the corrdinates of the bug are manually encoded at the bottom right corner for clarity.

![image](https://user-images.githubusercontent.com/66165922/159823443-82239655-1abd-4728-9d92-2d54788854f4.png)

I run the motif search on the input image and plot the coordinates found by the search...

![image](https://user-images.githubusercontent.com/66165922/159824039-9ea95671-add8-4a31-b4b8-7584988b9c71.png)



View code on [NBviewer](https://nbviewer.org/github/vineetver/Object-Detection-Without-OpenCV/blob/main/bug.ipynb)
