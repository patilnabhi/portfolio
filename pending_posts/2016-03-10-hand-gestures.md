---
layout: post
title:  "Hand Gesture Recognition"
date:   2016-03-10 13:00:00
last_modified_at:  2016-03-15 13:00:00
excerpt: ""
categories: project
tags:  hand gesture recognition, OpenCv, robotics, ROS
image:
  feature: update.jpg
  topPosition: 0px
bgContrast: dark
bgGradientOpacity: darker
syntaxHighlighter: no
---

***This is part of a [ROS] project developed during the winter quarter at Northwestern University ([NU]) as part of M.S. in Robotics (MSR) program.
(ROS stands for Robot Operating System).***

####Project Website:
* [http://patilnabhi.github.io/tbotnav] 

####Goal:

* Using a kinect, OpenCV and ROS, develop an API to recognize number of fingers from 0 to 5

####Tasks:

* This project can be broken down into 5 main tasks:

1. **Extract hand region from kinect depth data:**   
<br>
2. **Determine convex hull and convexity defects of extracted hand region:**    
<br>
3. **Detect no. of fingers using the convexity defects from (2):**  
<br>
4. **Create a custom image window to show the recognition in real-time:**  
<br>
5. **Integrate with ROS:**  

####Future work:
    
* Improve the fingers recognition results by combining with skin-color segmentation and machine learning

**References:**


[http://patilnabhi.github.io/tbotnav]: http://patilnabhi.github.io/tbotnav
[ROS]: http://www.ros.org/
[NU]: http://www.mccormick.northwestern.edu/robotics/
[OpenCV]: http://opencv.org/
[Rviz]: http://wiki.ros.org/rviz