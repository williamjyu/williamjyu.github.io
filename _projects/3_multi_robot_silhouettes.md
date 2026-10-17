---
layout: page
title: Multi-Robot Silhouettes
description: A multi-robot shadow-art pipeline that turns video into shadow animations on physical robot arms.
importance: 3
---

**Multi-Robot Silhouette Matching & Trajectory Optimization**

Built a multi-robot shadow-art pipeline that converts source video into binary silhouette targets, optimizes 5 arm poses, and deploys the shadow animations to physical robot hardware.

- Implemented SAM 2 video segmentation to extract silhouette targets.
- Built a baseline CMA-ES optimizer with staged search and collision-aware scoring.
- Added live MuJoCo visualization to compare against a JAX pipeline.

[Code on GitHub](https://github.com/soujanya957/fleet-shadow-art)
