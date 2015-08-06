---
layout: post
title:  "Automated Greenhouse"
date:   2015-08-05 11:14:36
categories: blog
---


Another project I worked on last semester (although less cool than a line-following, package-delivering robot) was an automated greenhouse. Now by automated I don't mean it fed itself and took out the trash without you telling it to, I mean that it would change the temperature to reach a specific set point at any given time. With the help of an Arduino UNO and temperature sensors, we were able to create a greenhouse that would open and close its roof to lower or raise the temperature inside. This allowed us to give it a certain temperature set-point deemed healthy for the plant, and allow the greenhouse to keep the temperature within one degree of that set-point automatically. An image of the greenhouse can be seen below:

<img src="/assets/greenhouse1.JPG" width="70%" />

An Arduino ethernet shield was used to collect temperature data, both inside and outside, and put it on an SQL database. We then created a website that displayed this data and allowed you to change the setpoint accordingly. More images of the greenhouse and how it was wired can be seen below:

<img src="/assets/greenhouse2.JPG" width="70%" />

The resistors used to heat the inside of the greenhouse.

<img src="/assets/greenhouse3.JPG" width="70%" />

Circuitry.

<img src="/assets/greenhouse4.JPG" width="70%" />

More circuitry. LED Screen to display current indoor/outdoor temp and set-point.



--- Jamel Charouel

Wednesday, August 5th, 2015