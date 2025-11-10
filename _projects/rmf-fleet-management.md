---
layout: project
title: RMF Robot Fleet Management Simulation
permalink: /projects/rmf-fleet-management/
description: Implementation of multi-robot cleaning and patrol scheduling using the Robotics Middleware Framework (RMF) within a Gazebo simulation.
category: work
# If you have a primary image to represent the project (e.g., a simulation screenshot), add it here:
# img: assets/img/rmf_rectorate.png 
github: jordialt/ir2134
# website: # Add a link to a video demo if available
---

This project was developed for a course in **Robotic Intelligence** focusing on the deployment and coordinated operation of autonomous mobile robots in a structured indoor environment.

It utilizes the **Robotics Middleware Framework (RMF)** to simulate a fleet of diverse robotic agents (including `cleanerBotA` and `tinyRobot`).

Key implementations focused on:
* **Environment Mapping:** Configuring the **Rectorate** building map with navigation graphs and points of interest for RMF dispatch.
* **Task Scheduling:** Defining and submitting complex tasks, specifically a **Cleaning** task (using `cleanerBotA`) and a **Patrol** task (using `tinyRobot`).
* **Multi-Robot Coordination:** Leveraging RMF to handle traffic management, path planning, and conflict resolution between the heterogeneous robot fleet in the shared simulated space.
