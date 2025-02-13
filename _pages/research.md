---
layout: archive
title: "Selected research topics"
permalink: /research/
author_profile: true
---

### Scattering problems in unbounded interfaces
I have developed a method for solving a class of decomposable scattering scattering problems in complicated unbounded domains. If the computational domain can be split into simple subdomains (such as straight waveguides or periodic gratings), then the domain Green's functions for each piece can be used to reduce the scattering problem to an integral equation on the domain boundaries. The resulting integral equation can then be analytically continued to the complex plane, where it can be safely truncated and discretized using standard integral equation techniques.

<p float="left">
  <img src="https://github.com/user-attachments/assets/2816d9da-41f6-4f4a-bfea-acee4ac6d43e" width="32%" align="middle"/> 
  <img src="https://github.com/user-attachments/assets/365c0fd0-b8bb-4474-8536-103d21b0b5cc" width="26%" align="middle"/> 
  <img src="https://github.com/user-attachments/assets/cb71b2da-433f-4359-9758-0140b785074f" width="28%" align="middle"/>
</p>


### A fast solver for surface PDEs
I showed that 2D Green's for elliptic problems can be used to reformulate elliptic surface PDEs as a well conditioned surface integral equation. I then developed a singular quadrature scheme and fast direct solver allowing the resulting integral equation to be accurately discretized and efficiently solved. I have used this method to solve a variety of problems, including eigenvalue problems, oscillatory problems on unbounded surfaces, and as an implicit time stepper for hyperbollic equations.
<p float="left">
  <img src="https://github.com/user-attachments/assets/d4ea7161-ec08-4b59-bc32-2e784c322330" width="55%"  align="middle"/>  
  <img src="https://github.com/user-attachments/assets/4172c756-204d-48e7-b3ae-934b84d38e23" width="38%"  align="middle"/>
</p>

<img src="https://github.com/user-attachments/assets/76a41859-c808-45b0-9271-a36d03aaf94e" width="32%" />

![](../images/surface_GL.mp4)

### A domain decomposition method for waveguide circuits
I have demonstrated how a complicated photonic circuit can be efficiently be simulated by constructing impedance to impedance maps for individual circuit elements and then recursively merging elements by merging their impedance to impedance maps. When circuit elements are connected by straight pipes, these maps can be greatly compressed by projecting the impedance data onto the modes for each pipe.

<img src="https://github.com/user-attachments/assets/d30d5f61-250d-490f-8f79-ed0d7a55717f" width="40%" />



