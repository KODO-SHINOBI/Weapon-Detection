# Weapon Detection Using YOLO
<br />
<p>Here we will introduce you about YOLO and how to use it as Object Detection Model.</p>
<br />

<h1>Little About YOLO</h1>
<br />
<p>You Only Look Once abbreviated as YOLO is an object detection algorithm. It is basically a single convolutional network predicts the bounding boxes and the class probabilities for those boxes. </p>
<br />

<h1>Why YOLO?</h1>
<p>YOLO is orders of magnitude faster(45 frames per second) than other object detection algorithms.</p>
<br />

<h1>How To Use yolo.py</h1>
<p><b>Usage:</b></p>
<p> yolo.py [-h] [--webcam WEBCAM] [--play_video PLAY_VIDEO]</p>
<p>[--image IMAGE] [--video_path VIDEO_PATH]</p>
<p> [--image_path IMAGE_PATH] [--verbose VERBOSE]</p>
<p><b>optional arguments:</b></p>
<p>  -h, --help , show this help message and exit</p>
<p> --webcam WEBCAM , True/False</p>
<p> --play_video PLAY_VIDEO , Tue/False</p>
<p> --image IMAGE , Tue/False</p>
<p> --video_path VIDEO_PATH , Path of video file</p>
<p> --image_path IMAGE_PATH , Path of image to detect objects</p>
<p> --verbose VERBOSE , To print statements</p>
<p>Weights File Backup</p>
<p><b>If the GitLFS file is not accessible - Download Weights and keep inside the project folder.</b></p>
<p><b>Move inside the project folder and use the following command:</b></p>
<p>python yolo.py --play_video True --video_path videos/1.mp4</p>
<p>or</p>
</p>python yolo.py --image True --image_path Images/1.jpg</p>
<br />

