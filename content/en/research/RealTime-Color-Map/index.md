---
title: "Research on Real-Time Color Map Reconstruction Using Vision-LiDAR-IMU Fusion"
summary: "SLAM, Sensor Fusion, 3D Reconstruction"
date: 2024-04-14 
featured: true
# 详情页面的 社交按钮图标 不展示 
share: false

---


Existing LiDAR-inertial-visual odometry and mapping (LIV-OAM) systems mainly utilize the LiDAR-inertial odometry (LIO) module for structure reconstruction and the LiDARassisted visual-inertial odometry (VIO) module for color rendering. However, the performance of existing LiDAR-assisted VIO module doesn’t match the accuracy delivered by LIO systems in the scenarios containing rich textures and geometric structures. This project introduces SR-LIVO, an advanced and novel LIV-OAM system employing sweep reconstruction to align reconstructed sweeps with image timestamps. This allows the LIO module to accurately determine states at all imaging moments, enhancing pose accuracy and processing efficiency. Experimental results on two public datasets demonstrate that:  

1. our SR-LIVO outperforms the existing state-of-the-art LIV-OAM systems in both pose accuracy, rendering performance and runtime efficiency;

2. In scenarios with rich textures and geometric structures, the LIO framework can provide more accurate pose than existing LiDAR-assisted VIO framework, and thus helps rendering.
