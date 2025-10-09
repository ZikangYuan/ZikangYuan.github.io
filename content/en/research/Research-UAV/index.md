---
title: "Research on UAV Autonomous Exploration Systems Based on Point Cloud Data"
summary: "Autonomous Exploration, UAV"
date: 2025-08-01 
featured: true
# 详情页面的 社交按钮图标 不展示 
share: false

---

In this project, we propose a novel LiDAR-based aerial exploration framework that enables coverage path guidance in large-scale point cloud maps. Although recent coverage path guidance-based methods mitigate the frequent revisitations of previously explored zones by temporarily incorporating the centers of unknown zones as nodes into the topological graph and driving UAVs toward these positions, the creation of topological nodes in unknown zones relies on the occupancy state of each volume in the scenario. This necessitates a memory-intensive occupancy grid-based map representation, which is difficult to be applied in large-scale scenarios. To address this limitation, we propose a method for distinguishing between explored and unknown zones directly in point cloud maps, thereby enabling the creation of topological nodes in unknown zones without relying on occupancy grids. Furthermore, we adopt a hierarchical global planning strategy combining coverage path planning with local path refinement, which not only guides the UAV toward unknown zones but also ensures smooth trajectory execution. Experimental results on two large-scale simulated environments demonstrate the high efficiency of our framework, which both eliminates frequent revisitations of previously explored zones and reduces exploration time compared to state-of-the-art approaches.
