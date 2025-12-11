---
layout: project
title: Systems Mechanical Dissection
description: Took Apart a Sphero SPRK+ Robot
technologies: ChatGPT, MATLAB
image: /assets/images/Sphero_SPRK+.jpg
---

For a class, we were asked to dissect a mechanical design. The design was a Sphero SPRK+ Robot.

In addition to this, we made a 10 page report discussing ODE derivations, the transfer functions, battery model, block diagram, and plots. My part was the battery model, where I developed a model of the Sphero’s 3.7V 350 mAh Li-Po cell using a dual-RC equivalent circuit, derived the governing ODEs for the transient voltage response, identified the fast and slow time constants associated with internal resistance and diffusion effects, and showed how these dynamics explain the voltage sag and recovery the robot experiences during rapid motor load changes.

[Report]({{ '/MAE3260 Spherologists Final Groupwork Report.pdf' | relative_url }})