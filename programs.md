---
layout: page
title: Programs
permalink: /programs/
---
Here some programs I have made that may be useful for other researchers/students are kept. These are as error free as possible, but almost definitely aren't 100% perfect - let me know if you find errors! Everything is written in Python.




#### Knife-edge beam profiler fitting
<a href="../programs/knife_edge_fit.py" target="_blank"> This program </a> allows you to calculate the size of a laser beam simply by measuring the beam power on a power meter, and then scanning a razor blade (or other sharp object) through the face of the beam. Recording the transmitted power as a function of the razor blade position can then be fitted to a function that allows the beam radius (1/e^2) to be calculated. <a href="../pdfs/knife_edge_profiler.pdf" target="_blank"> A PDF </a> explaining how I derived the equation to fit to is here, for reference. The program is pretty self-explanatory and simple, but assumes that you are measuring the stage position in millimetres. It was intended initially for measuring on unfocussed beams, but could also be used with a focussed beam provided that you don't burn the knife edge. Commented out in the program is some example data I took from one of the laser systems in my lab. 
