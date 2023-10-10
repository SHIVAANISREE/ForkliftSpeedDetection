<div align=center>
<h1><center>Forklift Speed Detection</center></h1>
</div><br><br>

<p align=center>
  <img src="https://github.com/SHIVAANISREE/ForkliftSpeedDetection/assets/110712340/a3c9c1da-da1b-46c3-85f0-17d568b8934f.gif" width="500" height="500">
</p>

<h3>About</h3>
<ul>
  <li>This Project focuses on estimating the speed of forklifts using computer vision and object tracking techniques. Forklifts are essential vehicles in industrial settings, and monitoring their speed can be crucial for safety and efficiency.</li><br>
  ✅Object Detection: Using Deep Learning model for object detection to identify forklifts in video frames.<br><br>
  ✅Object Tracking: Using Tracking algorithms to follow the movement of forklifts across frames.<br><br>
  ✅Speed Estimation: By Measuring the distance travelled by a forklift between frames and considering the frame rate, estimate its speed in kilometers per hour(km/hr).<br><br>
  ✅Real-Time Visualization: The project provides real-time visualization of tracked forklifts and their estimated speeds.<br><br>
</ul>

<h2>Technologies Used</h2>

<p align="center">
  <img src="https://github.com/SHIVAANISREE/ForkliftSpeedDetection/assets/110712340/a14f4bda-6ded-4dc9-a046-9f6e51a9357c.gif" width="250" height="250">
</p>

The [OpenCV](https://opencv.org/) is the huge open-source library for the computer vision, machine learning, and image processing and now it plays a major role in real-time operation which is very important in todays systems. By using it, one can process images and videos to identify objects, faces, etc,.
<p></p>

<h2>Methodology</h2>
<ul>
  <li>This project can be useful in industrial and warehouse settings to monitor forklift speeds, aiding in safety and operational optimization.</li>
  <h3>Packages and Libraries</h3>
  <h5>✅OpenCV(Open Source Computer Vision Library):</h5>
  <ul>
    <li>OpenCV is a widely used computer vision library in the field of image and video analysis.</li>
    <li>It provides functions for reading, processing and displaying images and videos.</li>
    <li>In this script, OpenCV is used for video capture, image resizing, drawing rectangles around detected objects and displaying video frames.</li>
  </ul>
    <h5>✅Dlib:</h5>
  <ul>
    <li>Dlib is a C++ library containing tools and algorithms for machine learning, computer vision, and image processing.</li>
    <li>In this script, Dlib is used for object tracking with the correlation tracker.</li>
    <li>It helps in associating objects detected in one frame with their corresponding tracks in the next frame.</li>
  </ul>
  <h5>✅MobileNet-SSD:</h5>
  <ul>
    <li>MobileNet-SSD is a deep learning model used for object detection.</li>
    <li>The script loads pre-trained MobileNet-SSD weights and config files to detect vehicles (cars and buses) in each frame.</li>
    <li>It utilizes the MobileNet-SSD model to identify objects in the video frames and provides their class labels and confidence scores.</li>
  </ul>
  <h5>✅Threading:</h5>
  <ul>
    <li>Python's threading module is used to run the object tracking and video processing logic concurrently.</li>
    <li>Threading allows you to perform tasks in parallel, which can be beneficial for real-time video processing.</li>
  </ul>
  <h5>✅Mathematical Calculations:</h5>
  <ul>
    <li>The script includes mathematical calculations to estimate the speed of vehicles based on their locations in consecutive frames.</li>
    <li>It calculates the distance traveled by a vehicle and uses the frame rate (fps) to estimate the speed in kilometers per hour (km/hr).</li>
  </ul>
  <h5>✅IPython Display:</h5>
  <ul>
    <li>The IPython display library is used to display video frames within an IPython environment.</li>
    <li>It helps in showing the processed frames with tracked objects and their speed information in real-time.</li>
  </ul>
  <h5>✅Image and PIL (Python Imaging Library):</h5>
  <ul>
    <li>The script uses the BytesIO and PIL libraries to convert the processed frames from OpenCV format to a format suitable for display in IPython.</li>
    <li>BytesIO is used to store the image data in memory, and PIL is used to convert and display the images.</li>
  </ul><br><br>


  <p>The following image is the output of the Forklift Speed Limitation.</p>
  <p align="center">
    <img src="https://github.com/SHIVAANISREE/ForkliftSpeedDetection/assets/110712340/14c843df-6d2b-4314-9260-171a66ace3dc.jpg">
  </p>
  <p>The project combines computer vision techniques, deep learning for object detection, and multi-threading to perform real-time vehicle tracking and speed estimation in a video feed. It leverages the capabilities of OpenCV, Dlib and MobileNet-SSD to achieve the accurate prediction.</p>
</ul>


