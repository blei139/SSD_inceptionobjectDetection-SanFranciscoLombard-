# SSD_inceptionobjectDetection-SanFranciscoLombard-
This repository is a SSD Inception object detection project, using the dash camera videoes taken from streets of Lombard and Marina District areas in San Francisco. The object detection algorithm is SSD Inception. The SSD Inception model is 'ssd_inception_v2_coco'. The object detection graph is 'frozen_inference_graph.pb', which has weights baked into the graph as constants and used by tensorflow for object detection. The ipython script, is SSDobjectDetectionVideoProc.ipynb. This script detects objects such stop signs, persons, cars, trucks, bicycles, and traffic lights. This script processes each frame in the input video by detecting objects, using openCV to detect traffic light color specifically for traffic lights. Then, it passes the processed image in each frame into a stream output video with SSD object detection and openCV traffic light color detection.
Instruction to run python script: At the linux or ubuntu prompt, type this command in the object_detection directory: python SSD_InceptionobjectDetectionVideoProc.py .

The SSD Inception object detection method is a little slower than SSD mobilnet from my observation.

Here are the youtube links:

https://youtu.be/gotpOmxZMxM

https://youtu.be/M_VFFScocQQ

https://youtu.be/yziyTTFeXoM
