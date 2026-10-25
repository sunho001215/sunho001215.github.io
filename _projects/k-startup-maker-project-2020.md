---
title: K-Startup Maker Project 2020
description: Maker project supported by the Korean government (K-Startup)
summary: Controlling a TurtleBot without any onboard sensors, using external cameras with U-Net driving-area detection and DOPE robot pose estimation trained in a ROS Gazebo simulation.
start_date: 2020-07-01
end_date: 2020-12-31
tags: [Autonomous Driving, Computer Vision, Localization]
cover: /assets/img/projects/k-startup-maker-project-2020/cover.jpg
cover_position: 22%
---

## Project Description

This is one of the Maker projects supported by the Ministry of SMEs and Startups of South Korea, which encourage creative work that uses digital devices and various tools to bring ideas to life. The program is open to everyone from high school and university students to working professionals.

## Details

The goal of this project was to control a robot without attaching any sensors to it other than its actuators. We set this goal because the many sensors typically mounted on robots raise production costs, making it harder for robots to be widely adopted in society. To control the robot, we installed multiple external cameras and performed driving-area detection with U-Net and robot pose detection with DOPE. To generate training data, we built a ROS Gazebo simulation environment and then applied the trained models in a real-world setting. I served as the overall team leader, and we used TurtleBot as our robot platform. ([GitHub](https://github.com/snuzero2020/zero_maker))

## Remarks

This project was carried out with a grant of $5,000. The same work was also conducted as the [X-Corps Project 2020](/projects/x-corps-project-2020/).

## Images

{% include figure.html src="/assets/img/projects/k-startup-maker-project-2020/turtlebot.jpg" caption="TurtleBot" %}

{% include figure-row.html images="/assets/img/projects/k-startup-maker-project-2020/unet-1.png,/assets/img/projects/k-startup-maker-project-2020/unet-2.png" caption="Driving area detection (U-Net)" %}

{% include figure-row.html images="/assets/img/projects/k-startup-maker-project-2020/dope-1.png,/assets/img/projects/k-startup-maker-project-2020/dope-2.png" caption="Robot pose detection (DOPE)" %}

## Video

{% include video.html src="/assets/video/sensorless-robot-control.mp4" poster="/assets/img/projects/k-startup-maker-project-2020/video-poster.jpg" %}
