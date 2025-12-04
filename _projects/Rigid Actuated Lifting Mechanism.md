---
layout: project
title: 2D Actuated Lifting Mechanism (Rigid)
description: I designed a lifting mechanism with given constraints that would lift the maximum possible weight to the highest possible height. 
technologies: [Statics]
image: https://github.com/Cornell-MAE-UG/fa25-portfolio-jc3664/blob/main/assets/images/Hw5.jpg
---

Problem Definition: 

Given a 2D design space of 150cm long and 50cm tall, a bar of a fixed length (your
choice), 3 pin supports of which two need to be mounted on the ground and a linear
actuator (pick from online catalog, use max force values only), design a
frame/mechanism to lift the maximum possible weight to the highest possible height.
Assume all the support and actuator are rigid.

Constraints: 
- Pin Supports: 3 total, with 2 mounted on the ground
- Mechanism must fit in 150 cm x 50 cm space 
- All elements rigid 

Objectives: 
- Lift the greatest possible load 
- Maximize height 

Design Degrees of Freedom: 
- Type of Actuator: ERD 
    - Max Force: 2 kN
- Length of Rigid Bar 
    - 20 cm 

Static Analysis: 
By drawing free-body-diagrams (FBDs) for each bar in the design, I solved for the maximum weight  the structure could support. Using moment equilibrium about points A and D, I was able to calculate the gravitational force from the lifted box and therefore, the maximum weight the structure can safely carry. 