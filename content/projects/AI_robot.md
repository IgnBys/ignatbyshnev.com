---
title: "AI intelligent robot"
date: 2023-03-09T15:24:13Z
draft: false
---

## About

The essence of the project is to create a robot to simulate the process of working in a warehouse. Customers bring parcels to the warehouse, which the robot must pick up from a certain place and take to an empty shelf designated specifically for a certain type of parcel (sports, food, books, clothes, etc.). Simulation of customers occurs by generating parcels in a specially designated place. When working, the robot must take into account some parameters:
- its charge level
- the closest path to the designated place where it must put the parcel
- be able to assess the complexity of the chosen path in accordance with the time spent on passing the path (1 cell is considered as 1 unit of time, if there is a shelf on the cell - 10 units of time)
- decide which of the parcels to give to the client first / pick up from the client, depending on the time that customers are waiting for service
- decide which of the parcels to give to the client first / pick up from the client, depending on the time they lie in the warehouse


## Technologies 

Python, pandas, NumPy, PIL, tensorflow 

## My tasks

- expanded of the **shortest path search algorithm** for the robot to perform assigned tasks
- optimized and processed data using **pandas** and **NumPy** libraries
- built a graphical interface in Python using **PIL**
- creating own dataset
- training robot model with **tensorflow**
- managed project workflow using **Jira** and **Git** version control

## How does it look
<video width="640" height="360" controls>
  <source src="/ai_robot.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>