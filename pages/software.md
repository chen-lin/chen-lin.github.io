---
layout: page
title: Software
permalink: /software/
---

The following tools I have developed in my research can be found at [GitHub](http://github.com/chen-lin).

## openmoor

Openmoor is an open-source program for simulating mooring systems in offshore floating wind turbines and wave energy devices. Find the source code and examples at [GitHub](https://github.com/chen-lin/openmoor/) and the tutorial on openmoor official [website](https://openmoor.github.io).

Below is an example of using openmoor to simulate the motions of a mooring cable model subjected to forced motions at the top end for two cases:
- Case 1: forced upper end circular motion with radius 0.2 m and period 3.5 s
- Case 2: forced upper end circular motion with radius 0.2 m and period 1.25 s

![](https://github.com/chen-lin/OpenMOOR/blob/master/examples/validation/Case3-5.gif?raw=true) | ![](https://github.com/chen-lin/OpenMOOR/blob/master/examples/validation/Case1-25.gif?raw=true)
:---:|:---:
Case 1 | Case 2


## farx
Fractional-order AutoRegressive model with eXogenous variables (FARX) for building thermo-dynamics can achieve comparable accuracy as classical ARX models while with a largely reduced number of parameters. This largely reduces the identification cost in system identification, therefore facilitating the model-predictive control. Find the code and an example [here](https://github.com/chen-lin/farx/).