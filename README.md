## About The Project

This notebook demonstrates multidimensional motif search in python.

In this notebook I consider a simple case:

* I have a image of chickens
* Inside image of chickens theres a bug
* I want to find the coordinates of the bug

This notebook does not use any image detection or pattern matching algorithms/libraries. OpenCV is only used for I/O.

For the input image below, in which the corrdinates of the bug are manually encoded at the bottom right corner for clarity.

![image](https://user-images.githubusercontent.com/66165922/159823443-82239655-1abd-4728-9d92-2d54788854f4.png)

I run motif search on the input image and plot the coordinates found by the search...

![image](https://user-images.githubusercontent.com/66165922/159824039-9ea95671-add8-4a31-b4b8-7584988b9c71.png)

## Getting Started

### Dependancies

List of all the libraries you need to run the code.

  ```sh
  Python 3.x
  Numpy
  Matplotlib
  Opencv-python
  Stumpy
  ```
  
### Usage

  ```sh
  $ conda create -n "env-name" python=3.x, anaconda, opencv-python, stumpy
 
  $ conda activate "env-name"
  
  $ cd Object-Detection-Without-OpenCV
  
  $ jupyter notebook
  ```

### View the code

[NBviewer](https://nbviewer.org/github/vineetver/Object-Detection-Without-OpenCV/blob/main/bug.ipynb)

## License

Distributed under the MIT License. See `LICENSE.md` for more information.


## Contact

Vineet Verma - vineetver@hotmail.com - [Goodbyeweekend.io](https://www.goodbyeweekend.io/)
