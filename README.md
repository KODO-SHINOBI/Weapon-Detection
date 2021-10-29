# Weapon Detection Using YOLO
<p><b>Note :- The model we have programmed is in general form which means you can used this model to lern and detect object of your choice.</b></p>
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
<br /><br />

<h1> Breakdown Of Program , How Program Works , & What Resources Needed</h1>
<br />
<h3>Importing Modules</h3>
<p>We must need to include these modules at first. And if the module is missing then you must install it first.Then You can import it as shown.</p>
<img src=" " alt="importing module"/>
<br />

<h3>Functions & Their Use</h3>
<p>1.Below shown function is used to load yolo.</p>
<img src=" " alt="load_yolo function"/>

<p>2.This function is used to read images from the file specified.</p>
<img src=" " alt="load_image function"/>

<p>3.This function is used to detect objects in the images being loaded.</p>
<img src=" " alt="image_detect function"/>

<p>4.This function is used to start webcamp to take real-time images/recordings.</p>
<img src=" " alt="start_webcam function"/>

<p>5.This function is used to specified objects in the webcam recording.</p>
<img src=" " alt="webcam_detect function"/>

<p>6.This function is used to detect objects in videos.</p>
<img src=" " alt="start_video function"/>

<p>7.This function is used to get the dimensions of specified objects only.</p>
<img src=" " alt="get_box_dimensions function"/>

p>8.This function is used draw labels around the specified object with their name and boxes surrounding them.</p>
<img src=" " alt="draw_labels function"/>

p>9.Incomplete.</p>
<img src=" " alt="display_blob function"/>

p>10.Incomplete.</p>
<img src=" " alt="detect_object function"/>
