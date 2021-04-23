Requirement:
- Windows 10
- Webcam
Please follow these steps:
1. Download Python
Download : https://www.python.org/downloads/wind...​
2. Install Python
Tick add path
Make new folder on D, example: Python38
Point install on that folder
3. Check python and upgrade pip
$ python --version
$ pip --version
$ python -m pip install -–upgrade pip
4. Install numpy
$ pip install numpy
5. Install opencv
$ pip install opencv-contrib-python-headless
6. Check installed opencv
$ python
$ import cv2
$ cv2.__version__
7. Install tensorflow
$ pip install --upgrade tensorflow
check tensorflow
$ python
$ import tensorflow as tf
8. Install imutils
$ pip install imutils
9. For face mask detection, we must update the libraries suitable for face mask detection
$ pip install face-mask-detector
​11. Trial python code
Open cmd, run as administrator
Change directory to python code folder location using cd syntax

$ python detect_mask_video.py          ---- run a program

presss "q" for exict

thank you!