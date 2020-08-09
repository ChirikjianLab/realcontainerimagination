# Abstract

Open containers, i.e., containers without covers, are an important and ubiquitous class of objects in human life. In this work, we propose a novel method for robots to "imagine" the open containability affordance of a previously unseen object via physical simulations. We implement our imagination method on a UR5 manipulator. The robot autonomously scans the object with an RGB-D camera. The scanned 3D model is used for open containability imagination which quantifies the open containability affordance. This quantification is used for open-container vs. non-open-container binary classification. If the object is classified as an open container, the robot further imagines pouring into the object, again using physical simulations, to obtain the pouring position and orientation for real robot autonomous pouring. We evaluate our method on open container classification and autonomous pouring of granular material on a dataset containing 130 previously unseen objects with 57 object categories. Although our proposed method uses only 11 objects for simulation calibration (training), its open container classification aligns well with human judgements. In addition, our method endows the robot with the capability to autonomously pour into the 55 containers in the dataset with a very high success rate.

# Link
Paper: [arxiv](https://arxiv.org/abs/2008.02321)

# Introductory Video
Introductory video will be available soon!

# Author
[Hongtao Wu](https://hongtaowu67.github.io), [Gregory Chirikjian](https://www.eng.nus.edu.sg/me/staff/chirikjian-gregory-s/)

Laboratory for Computational Sensing and Robotics (LCSR), Johns Hopkins University

Department of Mechanical Engineering, National University of Singapore

# Supplementary Videos
In this section, we show more demos on **open containability imagination** and **autonomous pouring**.

The simulation videos are outputted by the Pybullet. Note that the runtimes for open containability imagination and pouring imagination reported in the video are evaluated without video visualization. 

More videos will be available soon!

## I) Open Containability Imagination Demo

### 1) Plate (Detailed with Explanations)
Labeled as an open container by the human annotator
<iframe width="640" height="360" src="https://www.youtube.com/embed/E8EwN65H2VM" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### 2) Chef Hat
Labeled as an open container by the human annotator
<iframe width="640" height="360" src="https://www.youtube.com/embed/PREPo-lRp58" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### 3) Cup
Labeled as an open container by the human annotator
<iframe width="640" height="360" src="https://www.youtube.com/embed/1SFRWyxcqKg" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### 4) Book
Labeled as a non-open container by the human annotator
<iframe width="640" height="360" src="https://www.youtube.com/embed/oKLJqdkz328" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## II) Autonomous Pouring Demo
All the objects evaluated on the autonomous pouring are labeled as open containers by the human annotator.

### 1) Candlestick (Detailed with Explanations)
<iframe width="640" height="360" src="https://www.youtube.com/embed/govo8w2uYVw" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### 2) Gravy Boat
<iframe width="640" height="360" src="https://www.youtube.com/embed/eQX2o7H9B0E" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### 3) Baking Cup
<iframe width="640" height="360" src="https://www.youtube.com/embed/ytmPhnVwCro" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### 4) Origami Cup
<iframe width="640" height="360" src="https://www.youtube.com/embed/LcM-r7Dwl0M" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>


