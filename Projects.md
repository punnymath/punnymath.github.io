---
analytics:
  provider: "custom"
layout: archive
permalink: /Projects/
author_profile: true
header:
    image: project.jpg
---

{{ page.excerpt | markdownify }}

# Projects

## Detection of Windmills from Satellite Images using Deep Neural Networks 
<medium>May 2017-July 2017</medium>

<p><b>Developed a neural network implementing the googLENET algorithm</b> to detect windmills in a satellite image at <b>ISRO, Jodhpur</b>.The network was concieved from a tensorflow API - TensorBox. In a three membered team I was assigned the role of extracting around 2000 satellite images and also pipelining the neural network. To get satellite images I <b>wrote scripts in Python that took in coordinates and downloaded the images from GoogleMaps</b>.The network will be<b> used by ISRO for the purpose of analysis and documentation</b>. </p>

## Effect of cutting tool parameters on surface roughness using Neural Networks
<medium>Feb 2017</medium>

<p>The drive behind the project was to <b>understand the cutting tool parameters that would result in the least surface roughness</b>. We, a two membered team, chose <b>64 combinations of feed, cutting speed and depth of cut </b>and worked on a rod of mild steel. At each trial we evaluated the surface roughness using a roughness tester. After completing this task we then used the <b>nntoolbox inbuilt within MATLAB</b> to process our data and also compute the optimal values of the cutting tool parameters</p>

<a name="robocon"></a>

## Trajectory planning for a two-degree of freedom robotic arm
<medium>September 2017</medium>

<p> Implemented <b>genetic algorithm</b> on <b>python</b> to calculate the most efficient path for a robotic arm consisting of two links. The task for the arm is to travel in the most efficient fashion from a given <b>start point</b> to a given <b>end point</b> with <b>multiple obstacles in space</b>. The task was also then ramped up to calculate efficiency for the same problem but with <b>3 arms</b>. The task was achieved by finding out 'n' points in space such that the path formed by interpolating those points does not generate an intersection between the link and the obstacle. Graphics was achieved using <b>Tkinter, turtle and matplot,</b> while the interpolation of the points of the path was done by using the <b>Hermite Polynomial</b>.</p>

## Designing and simulating a 3 axis micro accelerometer
<medium>November 2017</medium>

<p> Designed a <b>micro accelerometer</b> with <b>increased sensitivity</b> in the <b>two planar directions</b>(i.e x and y axis) than the existing accelerometers, and also incorporated measuring capabilities in the third(i.r z axis) direction. The model was designed on <b>SolidWorks</b> and simulated on <b>COMSOL</b>. The simulations showed maximum stress concentration occuring at the junctions between the proof mass and fingers. However this <b>stress was much less than the yield stress</b> of the material, thereby making this design feasible.</p>

## Designing and manufacturing an autonomous robot and a semi-autonomous robot
<medium>Mar 2016</medium>

<p> As part of <b>Team Robocon</b>,Bits Pilani, we built two robots to compete in a pan-Asia competition <a href="http://aburobocon.net/"><b>ABU-Robocon</b></a> 2016. Find out more about the project <a href="/Robocon2016/"><b>here</b></a>.</p>

## Designing and manufacturing a manual disk propelling bot
<medium>Mar 2017</medium>

<p>As part of <b>Team Robocon</b>,Bits Pilani, we built a robot to compete in a pan-Asia competition <a href="http://aburobocon.net/"><b>ABU-Robocon</b></a> 2017. Find out more about the project <a href="/Robocon2017/"><b>here</b></a>.</p>

## Self-Regulating Eye Distance Maintainer
<medium>Dec 2016 - Jan 2017 </medium>

<p>Worked on building a working model of a <b>device that could carry a smart phone while constantly monitoring and adjusting the distance of the eye from the phone screen to reduce any strain to the eye</b>. The model consisted of two arms being operated by a <b>pair of servo motors connected to an arduino</b>. The design was seleceted for the <b>second round of APOGEE, Bits Pilani</b>(The University Technical Fest) </p>

