## YOLO Object Detection in Image and Video Using YOLO

This project implements a object detection via video, and image detection using the YOLO algorithm. YOLO is an object detection algorithm that stands for You Only Look Once. I've implemented the algorithm from scratch in Python using pre-trained weights. YOLOv3 was published in research paper: <a href="https://pjreddie.com/media/files/papers/YOLOv3.pdf" rel="nofollow">YOLOv3: An Incremental Improvement: Joseph Redmon, Ali Farhadi</a> It's originally implemented in <a href="https://github.com/pjreddie/darknet">YOLOv3</a>.

The COCO dataset is used for training.

Object detection can be used via command prompt or GUI.

<table>
  <tbody>
	<tr align="center">
		<th><strong>Object Detection on Streets of USA </strong></th>
	</tr>
	<tr align="center">
		<td><img src="https://github.com/Darkphantom323/Object_Detection_In_Image_And_Video_Using_YOLO/blob/master/doc/detector1.gif"></td>		
	</tr>
	<tr align="center">
		<th><strong>Object Detection on Streets of UK </strong></th>
	</tr>
	<tr align="center">
		<td><img src="https://github.com/Darkphantom323/Object_Detection_In_Image_And_Video_Using_YOLO/blob/master/doc/detector2.gif"></td>
	</tr>
	<tr align="center">
		<th><strong>Object detection in a Image </strong></th>
	</tr>
	<tr align="center">
		<td style="width: 100%;"><img src="https://github.com/Darkphantom323/Object_Detection_In_Image_And_Video_Using_YOLO/blob/master/doc/webcam_detector.jpg"></td>
	</tr>
</tbody>
</table>

Yolo is a deep learning algorithm that came out in May 2016 and it became quickly so popular because it’s so fast compared with the previous deep learning algorithm.
With Yolo we can detect real-time objects at a relatively high speed. With a GPU we would be able to process over 45 frames/per second while with a CPU around a frame per second.

OpenCV dnn module supports running inference on pre-trained deep learning models from popular frameworks like Caffe, Torch and TensorFlow.

## Requirement
<ul>
<li>OpenCV 4.2.0 or above </li>
<li>Python 3.6 or above</li>
</ul>

## Quick start
<ul>
  <li>Download official <a href="https://pjreddie.com/media/files/yolov3.weights" rel="nofollow">yolov3.weights</a> and place it under a folder called weight.</li>
  <li>Download official <a href="https://pjreddie.com/media/files/yolov3-tiny.weights" rel="nofollow">yolov3-tiny.weights</a> and place it under a folder called weight.</li>
  <li>Download <a href="https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg">yolov3.cfg</a> and place it under a folder called cfg.</li>
  <li>Download <a href="https://github.com/pjreddie/darknet/blob/master/cfg/yolov3-tiny.cfg">yolov3-tiny.cfg</a> and place it under a folder called cfg.</li>
</ul>

## Dependencies
<ul>
<li>Opencv</li>
<li>Numpy</li>
</ul>

## Install dependencies
<p><code>pip install numpy opencv-python</code></p>

## How to use?
<ol>
  <li>Clone the repository</li>
  <p><code>git clone https://github.com/muhammadshiraz/YOLO-Real-Time-Object-Detection.git<](https://github.com/Darkphantom323/Object_Detection_In_Image_And_Video_Using_YOLO/code></p>
</ol>
<ol start="2">
  <li>Move to the directory</li>
  <p><code>cd YOLO-Real-Time-Object-Detection</code></p>
</ol>
<ol start="3">
  <li>To use Object Detection in video</li>
  <p><code>python yolo_object_detection_video.py</code></p>
</ol>
<ol start="4">
  <li>To use Object Detection in Image </li>
  <p><code>python yolo_object_detection_image.py</code></p>
</ol>


