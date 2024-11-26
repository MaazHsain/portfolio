---
layout: project
type: project
image: img/cv/cv_thumb.jpg
title: "Traffic Monitoring System"
date: 2023-12-01
published: true
labels:
  - OpenCV
  - Computer Vision
  - Python
summary: "This project implements a computer vision-based traffic monitoring system to count and track vehicles in real-time video feeds. By using frame differencing and background subtraction techniques via openCV, the system accurately detects moving vehicles and calculates traffic flow rates. Key features include a configurable region of interest (ROI), dynamic buffer time to prevent double counting, and a real-time display of vehicle count and traffic rate."
---

<div class="text-center p-4">
  <img width="1287" height="736" src="../img/cv/cv_result_1.png" class="img-thumbnail" >
</div>

<span font-style="bold">Abstract</span><br>
This project involves the development of a computer vision-based traffic monitoring system designed to count and track vehicles in real-time video feeds. The system utilizes frame differencing and background subtraction techniques to accurately detect and highlight moving vehicles. The blue region is the region of interest, where the cars passing this region are detected. 

<span font-style="bold">Key Features:</span>
* Region of Interest (ROI): Focuses monitoring on a specific area within the video frame, reducing computational load and false positives.
* Dynamic Buffer Time: Prevents double counting of vehicles that momentarily leave and re-enter the ROI, adjustable based on traffic flow characteristics.
* Real-Time Display: Provides a live video feed with detected vehicles highlighted, along with continuously updated metrics for total vehicle count and traffic rate.
  
<span font-style="bold">Technical Approach:</span>
* Frame Differencing: Calculates the absolute difference between consecutive video frames to identify regions with significant changes indicating motion.
* Background Subtraction: Models the static background of a scene and subtracts it from the current frame to segment moving objects, enhanced by GaussianBlur and morphological operations to remove noise.

<span font-style="bold">Performance Metrics:</span>
* The system effectively calculates and displays the total car count and the rate of cars passing through the ROI per minute, offering valuable insights for traffic management and analysis.
* The modular and object-oriented design of the system ensures flexibility and ease of maintenance, making it adaptable to various traffic scenarios and enhancing its robustness and effectiveness.
