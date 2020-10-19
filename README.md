# Face Filter
You will be given an input image and two image templates one for sunglasses & another one is for mustache , your task is to overlay the eyeglasses and mustache on the given character. A sample input output is show below.
<img src = "https://minio.codingblocks.com/amoeba/jamie.jpg">

## Libraries
1. `cv2` for computer vision on images
    - `Install` with following command `pip install opencv-python` and `pip install numpy`
2. `numpy` for mathematical operations
    - `Install` with following command `pip install numpy`

## Cascades
1. ```haarcascade_frontalface_alt.xml``` *is to detect frontal face.*
2.  ```haarcascade_eye.xml```  *is to detect eyes both at once.*
3. ```Nose18x15.xml``` *is to detect nose.*

## How to run
1. Place you desired image in ```image``` folder.
2. In ```main.ipynb```, go to cell number 4 and change the file name.
For example, my image name is Before.png placed in ```images``` folder.
    ```image = cv.imread("images/Before.png", cv.IMREAD_COLOR)```
3. Now you can run the .ipynb file
   
