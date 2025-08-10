---
title: "Development of a Visual-Inertial Odometry Framework Based on Stereo Vision and IMU"
summary: "SLAM, Sensor Fusion, VIO, Localization"
date: 2025-08-10
featured: true
# 详情页面的 社交按钮图标 不展示 
share: false

---

In visual-inertial odometry (VIO) systems, allocating limited computational resources to constraints for new frames is more conducive to enhancing the accuracy of state estimation, as old frames have already undergone multiple updates. To enable VIO to efficiently index the observed map points of new frames in 3D space, this project proposes to introduce voxel map management to the VIO field and self-develop a stereo VIO system, named Voxel-SVIO. Based on the triangulation results of feature correspondences on current stereo image, we can directly index to the recently visited voxels in 3D space. The map points in these voxels can provide enough constraints for new frames, thus are suitable to be fed into the estimator. Experimental results on three public datasets demonstrate that our Voxel-SVIO outperforms most existing state-of-the-art approaches on accuracy, and the map points selected by recently visited voxels are crucial for ensuring the performance of the proposed system.

