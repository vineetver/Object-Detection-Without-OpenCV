<h2 align="center"> Multidimensional Motif Discovery</h2>

## Task Description

The task is to find the coordinates of the bug in a given image without using pattern matching libraries. The image is a
picture of multiple chickens in this case.

My solution is to convert the image into a time series of pixel values and then run a motif discovery algortihm to find
the coordinates of the bug.
Alternatively, I can use brute force by checking every possible combination of pixels.

Example:

Here is a picture with one bug. The coordinates are hard coded to troubleshoot the algorithm.

![image](https://user-images.githubusercontent.com/66165922/159823443-82239655-1abd-4728-9d92-2d54788854f4.png)

I run motif search on the input image and plot the coordinates using opencv.
The bold bounding box is the bug.

![image](https://user-images.githubusercontent.com/66165922/159824039-9ea95671-add8-4a31-b4b8-7584988b9c71.png)

## Dependencies

List of all the libraries you need to run the code.

  ```sh
  Python 3.x
  Numpy
  Matplotlib
  Opencv-python
  Stumpy
  ```

## Usage

  ```sh
  $ conda create -n "env-name" python=3.x, anaconda, opencv-python, stumpy
 
  $ conda activate "env-name"
  
  $ cd Object-Detection-Without-OpenCV
  
  $ jupyter notebook
  ```

## View code

[NBviewer](https://nbviewer.org/github/vineetver/Object-Detection-Without-OpenCV/blob/main/bug.ipynb)

## License

Distributed under the MIT License. See `LICENSE.md` for more information.

## Contact

Vineet Verma - vineetver@hotmail.com - [Goodbyeweekend.io](https://www.goodbyeweekend.io/)
