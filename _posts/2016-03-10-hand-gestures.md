---
layout: post
title:  "Hand Gesture Recognition"
date:   2016-03-10 13:00:00
last_modified_at:  2016-03-15 13:00:00
excerpt: ""
categories: project
tags:  hand gesture recognition, OpenCv, robotics, ROS
image:
  feature: hand_1.png
  topPosition: 0px
bgContrast: dark
bgGradientOpacity: darker
syntaxHighlighter: no
---

***This is part of a [ROS] project developed during the winter quarter at Northwestern University ([NU]) as part of M.S. in Robotics (MSR) program.
(ROS stands for Robot Operating System).***

**Project Website**
* [http://patilnabhi.github.io/portfolio/tbotnav] 

**Demo**

<p><center><iframe width="1920" height="1080" src="https://www.youtube.com/embed/u7TcyaLekFg" frameborder="0" allowfullscreen></iframe></center></p>

**Goal**

* Using a kinect, OpenCV and ROS, develop an API to recognize number of fingers from 0 to 5

**Tasks**

* The project can be summrized in the 5 following steps:

1. Extract hand region from kinect depth data  
2. Determine convex hull and convexity defects of extracted hand region 
3. Detect no. of fingers using the convexity defects from (2) 
4. Create a custom image window to show the recognition in real-time  
5. Integrate with ROS


**Future work**
    
* Improve the fingers recognition results by combining with skin-color segmentation and machine learning

**References:**

* [http://s-ln.in/2013/04/18/hand-tracking-and-gesture-detection-opencv/]
* [http://simena86.github.io/blog/2013/08/12/hand-tracking-and-recognition-with-opencv/]
* [http://euanfreeman.co.uk/openkinect-python-and-opencv/]


[http://patilnabhi.github.io/portfolio/tbotnav]: http://patilnabhi.github.io/portfolio/tbotnav
[ROS]: http://www.ros.org/
[NU]: http://www.mccormick.northwestern.edu/robotics/
[OpenCV]: http://opencv.org/
[Rviz]: http://wiki.ros.org/rviz
[http://s-ln.in/2013/04/18/hand-tracking-and-gesture-detection-opencv/]: http://s-ln.in/2013/04/18/hand-tracking-and-gesture-detection-opencv/
[http://simena86.github.io/blog/2013/08/12/hand-tracking-and-recognition-with-opencv/]: http://simena86.github.io/blog/2013/08/12/hand-tracking-and-recognition-with-opencv/
[http://euanfreeman.co.uk/openkinect-python-and-opencv/]: http://euanfreeman.co.uk/openkinect-python-and-opencv/