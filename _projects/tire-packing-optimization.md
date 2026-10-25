---
title: Tire Packing Optimization Project
description: Industry-sponsored project
summary: An automated robotic tire-packing system for FANUC industrial robots that maximizes the number of tires per collapsible rack and shipping container, using MILP or reinforcement learning, YOLO + SAM perception, and MPPI planning.
start_date: 2025-01-01
end_date: 2025-06-01
tags: [Robotics, Object Manipulation, Optimization, Computer Vision, Path Planning]
cover: /assets/img/projects/tire-packing-optimization/cover.jpg
cover_position: 15%
---

## Project Description

This industry project was conducted for Hankook Networks in collaboration with RASTECH. The goal was to improve tire transportation efficiency by maximizing the number of tires packed into a single shipping container. The task, previously performed by hand, is being automated with industrial robots, with the aim of exceeding human performance. A key challenge is maximizing tire packing density within collapsible racks.

## Details

We automated the tire-loading task for FANUC industrial robots by developing a system with two alternative approaches: (1) a mixed-integer linear programming (MILP) model and (2) a reinforcement learning algorithm, both designed to maximize the number of tires per collapsible rack and per shipping container. Both approaches use YOLO and SAM (Segment Anything Model) for tire detection and MPPI for real-time path planning. Both algorithms were successfully deployed on-site, and a [research paper](/#publications) describing the system is to appear soon.

## Video

{% include video.html src="/assets/video/tire-packing-demo.mp4" poster="/assets/img/projects/tire-packing-optimization/video-poster.jpg" %}
