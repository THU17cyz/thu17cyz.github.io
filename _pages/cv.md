---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## You can download the PDF version of my CV [here](https://thu17cyz.github.io/files/cv.pdf).

&nbsp;


Education
======
* B.E. in Software Engineering, Tsinghua University, 2017-2021 (expected)
  * Overall GPA **3.98**/4.0, ranking **1**/81
  * Major GPA **3.99**/4.0, ranking **1**/81
  * scored A+ (Top 1%) in 6 major courses

Publication
======
* He Wang\*, **Yezhen Cong**\*, Or Litany, Yue Gao and Leonidas J. Guibas. 3DIoUMatch: Leveraging IoU
  Prediction for Semi-Supervised 3D Object Detection. Submitted to *2021 IEEE/CVF Conference on
  Computer Vision and Pattern Recognition (CVPR)*. Under review. [link](https://thu17cyz.github.io/files/3dioumatch.pdf)

Research Experience and Projects
======
## **Stanford University, Computer Science Department, Apr. 2020 – Nov. 2020**
### *Research Assistant to Prof. [Leonidas J. Guibas](https://geometry.stanford.edu/member/guibas/), ACM fellow, IEEE fellow* 
### **3DIoUMatch: Leveraging IoU Prediction for Semi-Supervised 3D Object Detection**
* Proposed a novel semi-supervised method for 3D object detection based on pseudo-label propagation
along with a carefully designed filtering mechanism; This method outperformed the prior art significantly
under all settings on the two major indoor object detection benchmarks, ScanNet and SUNRGB-D
* Proposed leveraging predicted 3D IoU as localization confidence for pseudo-label filtering for the first time
in both 2D and 3D semi-supervised object detection to improve the localization quality of pseudo-labels
* Devised a differentiable 3D IoU module that enabled our localization filtering, IoU-guided NMS and IoU
optimization for bounding box refinement, and predicted IoU more accurately than previous designs
* Submitted a paper to CVPR 2021 as joint first author, currently under review

## **Tsinghua University, School of Software, Apr. 2019 – Nov. 2019**
### *Research Assistant to Assoc. Prof. [Yue Gao](http://www.gaoyue.org/en/people/gaoyue_index.html)* 
### **PointAlign: Towards Rotation Invariant Point Cloud Representation via Tangent Space Alignment**
* Proposed a method of hierarchically aligning point cloud to local tangent space, which could be easily
applied to multiple mainstream point cloud networks and make them invariant to arbitrary rotation.
* With our add-on method, RS-CNN could reach 90.8% classification accuracy under random SO(3) rotation
compared to 31.4% without our method on ModelNet40, outperforming the prior art remarkably
* Participated in Academic Promotion Program at Tsinghua University and awarded Outstanding Oral
Presentation. Submitted a paper to CVPR 2020 as joint first author

## **Tsinghua University, School of Software, Nov. 2018 – Feb. 2019**
### *Research Assistant to Assoc. Prof. [Yue Gao](http://www.gaoyue.org/en/people/gaoyue_index.html)* 
### **Visual Object Recognition**
* Studied how to learn joint representation of multimodal data for object recognition; Designed and
implemented several methods of fusing point cloud data and multi-view image data
* Won the First Prize in Scientific Research Training Program of School of Software, Tsinghua University

## **WeChat Mini-Program Development Competition 2020 [\[link\]](https://developers.weixin.qq.com/community/competition), May. 2020 – Aug. 2020**
### *Supervised by Assoc. Prof. [Qiang Liu](http://www.thss.tsinghua.edu.cn/publish/soften/3131/2010/20101219111048022743576/20101219111048022743576_.html)
* Designed a creative, playable and user-friendly WeChat Mini-Game called Yin-Yang with a classmate
* Implemented the game in JavaScript using Cocos Engine; Created the art resources ourselves with online resources and Photoshop; Improved the smoothness and speed of the game by using techniques such as resource preloading and node pool recycling
* Won the First Prize (4/171); Contacted by a game company for possible cooperation

## **Kaggle Open Images 2019 – Visual Relationship [\[link\]](https://www.kaggle.com/c/open-images-2019-visual-relationship), Aug. 2019 – Oct. 2019**
### *Supervised by Assoc. Prof. [Yue Gao](http://www.gaoyue.org/en/people/gaoyue_index.html)* 
* To provide high quality bounding boxes for detecting visual relationship, surveyed and compared many state-of-the-art 2D detectors; Preprocessed the raw data for training the detectors
* Inspired by several key improvements in SOTA detection methods, refined my own detection network based on YOLOv3 and obtained higher-quality bounding boxes, which improved the visual relationship detection performance, helping our team win Silver Medal

Work experience
======
## **Sensetime, Oct. 2020 – Present**
### *Research Intern at Department of Deep Learning Platform and Tools*
  * Supervisor: [Kai Chen](http://chenkai.site/)
  * Duties included: Participating in development of [MMDetection3D](https://github.com/open-mmlab/mmdetection3d)
## **Sensetime, Mar. 2020 – May. 2020**
### *Research Intern at EIG Research*
  * Supervisor: [Kai Chen](http://chenkai.site/)
  * Duties included: Research on instance segmentation based on [MMDetection](https://github.com/open-mmlab/mmdetection)

Selected Awards and Honors (In Chronological Order)
======
* **First Prize** in WeChat Mini-Program Development Competition 2020, Mini-Game Track (4/171 teams from universities all over China), 2020
* **National Scholarship** for 2019~2020 (Top 1% at Tsinghua University), 2020
* **National Scholarship** for 2018~2019 (Top 1% at Tsinghua University), 2019
* **SenseTime Scholarship** 2019 (29 recipients selected from all Chinese undergraduates), 2019
* **Undergraduate Student Travel Award** of MICCAI 2019 (45 recipients worldwide), 2019
* **Silver Medal** in Open Images 2019, Visual Relationship Track (Top 10% among 200+ teams), 2019
* **Outstanding Oral Presentation Award** in Academic Promotion Program of Tsinghua University, 2019
* **First Prize** in Scientific Research Training Program of School of Software, Tsinghua University, 2018
* **"12-9" Scholarship** for 2017~2018 (Top 1% at Tsinghua University), 2018

Skills
======
* Programming Skills
  * Fluent: Python, C/C++, JavaScript, PyTorch
  * Intermediate: Java, MATLAB, Assembly, LaTeX, TensorFlow, OpenCV
* Language Skills
  * Chinese: Mother tongue
  * English: Fluent, TOEFL (iBT) score 115 (R30, L30, S27, W28), GRE 339 (V169, Q170) +AW4.5
* Leadership
  * Extensive leadership experience –– Vice President of Student Union at School of Software at Tsinghua University, Class Monitor, Social Practice Team Leader


<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
