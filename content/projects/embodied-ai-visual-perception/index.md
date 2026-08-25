---
title: "Embodied Intelligence Visual Perception"
summary: "YOLO-based concrete crack detection used as visual priors to assist a SO-ARM101 robotic arm in planning operational poses, enabling grasping and placing of an accelerometer onto cracks."
tags:
  - Embodied AI
  - YOLO
  - Computer Vision
  - Robotics
date: "2026-08-24T00:00:00Z"
---

Based on the [LeRobot](https://github.com/huggingface/lerobot) framework and the SO-ARM101 robotic arm, introduced a YOLO object detection model to recognize concrete cracks. The detection results are used as visual priors to assist the robotic arm in planning operational poses, ultimately enabling the task of grasping an accelerometer and placing it onto the concrete crack on a real robotic arm.

{{< video src="yolo-lerobot.mp4" controls="yes" >}}
