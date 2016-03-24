---
layout: post
title:  "Face Recognition"
date:   2016-03-11 13:00:00
last_modified_at:  2016-03-15 14:00:00
excerpt: ""
categories: project
tags:  face recognition, face detection, OpenCv, fisherfaces, eigenfaces, robotics, ROS
image:
  feature: face_recog.png
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

<p><center><iframe width="1920" height="1080" src="https://www.youtube.com/embed/nvPzOo8tyUs" frameborder="0" allowfullscreen></iframe></center></p>

**Goal**

* Using a webcam, OpenCV and ROS, develop an API to recognize people in real-time

**Overview**

* The following flow-chart shows how the interface functions:

<center><img style="border: solid" src="{{ site.baseurl }}assets/images/posts/face-recog/flow_chart.png" width="100%"/></center>

<!-- 1. **Detect faces:**   
<br>
2. **Capture faces:**    
<br>
3. **Train face data using Fisher's Linear Discriminant Algorithm (LDA):**  
<br>
4. **Recognize faces:**  
<br>
5. **Create a simple GUI to capture and recognize faces:**  
<br>
6. **Integrate with ROS:**  -->

* Fisherfaces algorithm is implemented to train and recognize faces. The algorithm can be summarized as follows:

<center><img style="border: solid" src="{{ baseurl_posts_img }}/face-recog/fisher.png" width="100%"/></center>

**Future work**
    
* Improve accuracy of classification by combining various classifiers such as Principal Component Analysis (PCA), Independent Component Analysis (ICA) and LDA; this could be done using a Radial Basis Function (RBF)-based interpolation

<!-- **References:** -->


[http://patilnabhi.github.io/portfolio/tbotnav]: {{ site.baseurl }}/tbotnav
[ROS]: http://www.ros.org/
[NU]: http://www.mccormick.northwestern.edu/robotics/
[OpenCV]: http://opencv.org/
[Rviz]: http://wiki.ros.org/rviz