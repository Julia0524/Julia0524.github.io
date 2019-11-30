---
layout: archive
title: "Research and Project"
permalink: /project/
author_profile: true
---
------

## Real-Time Teeth Alignment Technology Based on Virtual Reality
### Mar. 2019 - Jun. 2019, Visual Media and Data Management Laboratory
### Supervised by Professor Bin Sheng
- Calculated oriented bounding box (OBB) and identified rotation axes (3 direction vectors) of each tooth using principal component analysis (PCA) in machine learning
- Developed 10 practical transformation modes (rotation around X/Y/Z axis and left/right/top/bottom side of the tooth, translation along X/Y/Z axis) in PC system with keyboard and mouse and in VR system using VRTK library in Unity
- Designed user interface for surgery simulation and data display including serial number and needed transformation distance of the chosen tooth; Calculated the final transformation matrix of each tooth
<span style="color:purple">**Here's a demo video showing the operation of our model!** </span> 
<iframe width="520" height="300" src="https://www.youtube.com/embed/pglWMPHbTlk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

------

## Reconstructing Teeth from a CT Scan 
### Sep. 2018 - Dec. 2018, Visual Media and Data Management Laboratory
### Supervised by Professor Bin Sheng
- Constructed teeth dataset by annotating teeth in CT scans using Photoshop and js-segment-annotator (a web tool for annotation)
- Designed a neural network based on SegNet using convolution and deconvolution to recognize and segment teeth parts in images converted from CT scans, with high accuracy of 99.5% in 300 pairs of testing samples
- Conducted edge extraction using canny operator in MATLAB, which applied Gaussian to smooth the image and two thresholds to extract edges; Extracted discrete points in images after edge extraction using OpenCV library
- Generated point cloud using PCL library by setting 3d coordinates of all points according to standard CT format and adding them to a ply model; Reconstructed 3D mesh model using MeshLab
<img src="https://raw.githubusercontent.com/Julia0524/Julia0524.github.io/master/images/TeethReconstruction_poster.png" width = "25%" alt="Poster of Teeth Reconstruction Project"/>

------

## ChinaVis 2019 Data Visualization and Analysis Challenge 
### May. 2019 - Jun. 2019, Data Visualization Course Project
### Supervised by Professor Xiaoju Dong
- Designed an interactive visual analysis system to predict the conference agenda, classify conferees, and analyze abnormal conditions using multi-view collaborative analysis
- Implemented 3 main views, 9 kinds of graphs (such as pie chart, pack chart, and treemap), and various interactive methods to demonstrate data from different dimensions such as time and space

------

## VR-Based Alpine Skiing Game for the 2022 Olympic Winter Games 
### Mar. 2019 - Jun. 2019, Science and Technology Innovation Project
### SJTU VR Education Center
- Designed the main architecture, detailed operation, user interface, and scenes of an interactive VR skiing action game
- Calculated sliding distance using a practical method of binding the collider to the bottom part of the ski sticks and recording the collision distance in order to simulate real-life operation in alpine skiing
- Integrated 2 different game modes (prop mode and gate mode) in 1 main scene in Unity; Traced real-time moving path of the player and generated props and gates automatically in suitable directions

------

## Pose Estimation from 2D RGB Images 
### Sep. 2018 - Jan. 2019, Digital Image Processing Course Project
### Supervised by Professor Bin Sheng
- Built 3 neural networks: HandSegNet for hand segmentation and cropping, PoseNet for hand key points detection and keypoint score maps prediction, Pose3DNet for the estimation of 3D normalized coordinates and hand pose
- Conducted multi-hand pose estimation by counting and cropping the hands respectively and integrating multiple hands estimated in 3D hand pose estimation network into one 3D coordinate system
<img src="https://raw.githubusercontent.com/Julia0524/Julia0524.github.io/master/images/PoseEstimation_poster.png" width = "25%" alt="Poster of Pose Estimation Project"/>
