# Python_yolov7-project
Task Description: Develop a computer vision system that:

1.Detects objects and their sub-objects. 2.Outputs hierarchical detection results in JSON format. 3.Supports retrieval of specific sub-object images. 4.Operates in real-time (10–30 FPS) on a CPU.

This task is performed on Google Colab Some basic technologies and framework used in implement this task are:- Deep learning framework- PyTorch Computer Vision- Object Detection and image processing libraries are OpenCV and Matplotlib Programming language : python

Approach : Firstly,Train Model yolov5 Get person detect Model Build hierarchy Create JSON Format files Analyze the images from yolov5 and returns it output in detection_output.json in JSON Format which shows Object and Sub-Object Detection and Analyze video from yolov5 and returns detection_result.json Find FPS of Inference Speed Optimization on CPU will be FPS: 2.82 for video and total CPU FPS Inference speed 20661.5960591133 FPS
