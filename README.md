RPi-OpenCV-Face-Rec-Python
==========================

Python Implementation of OpenCV Face Recognition taken from http://blog.oscarliang.net/raspberry-pi-face-recognition-opencv/.

This version uses a local camera plugged into the USB port.
<ol>
<li>Install appropriate libraries</li>
<i>sudo apt-get update
<br>sudo apt-get upgrade</br>
<br>sudo apt-get install python-opencv</i></br>

<li>Test python openCV - It will switch on the camera for video streaming if it is working</li>

<i>python test_python_openCV.py</i>

<li>Run face recognition code using trained face file</li>

Trained face file taken from http://stevenhickson-code.googlecode.com/svn/trunk/AUI/Imaging/face.xml

<br><i>python facedetect.py --cascade=face.xml 0</i></br>
</ol>
