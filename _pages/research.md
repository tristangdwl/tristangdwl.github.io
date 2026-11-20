---
layout: archive
title: "Selected research topics"
permalink: /research/
author_profile: true
---

### Proxy shells for fast summations

I recently showed that a series of proxy shells can be used to create small sets of equivalent charges that produce the same potential as a very large number of sources to very good accuracy. Unlike the popular proxy surface method, the proxy shell technique is based purely on smoothness and interpolation, and so does not require that the kernel satisfy a PDE uniqueness theorem. It is therefore applicable to a much broader range of kernels, such as Green's functions of nonlocal problems, Struve functions, and Matérn kernels. I have used the proxy shell technique to apply the precorrected-FFT, interpolative fast multipole, and recursive skeletonization methods to a wide variety of problems, including the Helmholtz-Beltrami equation and surface wave problems arising in cryoseismology.

<p float="left">
  <img src="{{ site.baseurl }}/images/proxy_shells_scattering.png" alt="Scattered wave field around multiple obstacles" width="42%" align="middle"/>
  <img src="{{ site.baseurl }}/images/proxy_shells_variable_helmbel.png" alt="Variable-coefficient Helmholtz solution on a curved surface" width="50%" align="middle"/>
</p>

### Surface waves

The vibrations in thin structures floating on water can be modeled by a nonlocal PDE on the fluid surface with high-order terms that capture features such as surface tension and rigidity. Cases where the boundary conditions jump order, such as at holes in floating ice sheets, are of particular interest. In my work, I have developed integral equation methods and fast algorithms for simulating scattering problems involving these jumps in order. I have also built custom singular quadratures that account for the singularities in the solution at these boundaries, allowing for high-order convergence.

<img src="{{ site.baseurl }}/images/ross_rift_4.png" alt="Wave scattering at an irregular interface, with enlarged views of the wave field" width="95%" />

### Scattering problems in unbounded interfaces
I have developed a method for solving a class of decomposable scattering problems in complicated unbounded domains. This method starts by splitting the computational domain into simple subdomains (such as straight waveguides or periodic gratings). The domain Green's function for each piece can then be used to reduce the scattering problem to an integral equation on the domain boundaries. The resulting integral equation can be analytically continued to the complex plane, where it can be safely truncated and discretized using standard integral equation techniques.

<!-- To upload an image, add it to the repo, then right click, "copy link" and paste it into the markdown" -->
<p float="left">
  <img src="https://github.com/user-attachments/assets/2816d9da-41f6-4f4a-bfea-acee4ac6d43e" width="32%" align="middle"/> 
  <img src="https://github.com/user-attachments/assets/365c0fd0-b8bb-4474-8536-103d21b0b5cc" width="26%" align="middle"/> 
  <!--<img src="https://github.com/user-attachments/assets/cb71b2da-433f-4359-9758-0140b785074f" width="28%" align="middle"/>-->
  <img src="https://github.com/user-attachments/assets/56204107-2d06-4ed0-877f-61b4a08794df" width="34%" align="middle"/>
</p>

### A fast solver for surface PDEs
I showed that a broad class of elliptic surface PDEs can be reformulated as well-conditioned surface integral equations using their 2D fundamental solutions. I then developed a singular quadrature scheme and fast direct solver which allow the resulting integral equations to be accurately discretized and efficiently solved. I have used this method to solve a variety of problems such as the surface Stokes equations, eigenvalue problems, and oscillatory problems on unbounded surfaces. I have also used it as an implicit time stepper for hyperbollic problems on surfaces.
<p float="left">
  <img src="https://github.com/user-attachments/assets/d4ea7161-ec08-4b59-bc32-2e784c322330" width="55%"  align="middle"/>
  <img src="{{ site.baseurl }}/images/unbounded_helmholtz_beltrami.svg" alt="Helmholtz-Beltrami wave field on an unbounded surface" width="32%" align="middle"/>
</p>

<p float="left">
  <!--<img src="https://github.com/user-attachments/assets/4172c756-204d-48e7-b3ae-934b84d38e23" width="38%"  align="middle"/> -->
  <img src="{{ site.baseurl }}/images/star_stokes.png" alt="Surface Stokes flow on a torus" width="38%" align="middle"/>
  <img src="{{ site.baseurl }}/images/stokes_bench.png" alt="Surface Stokes benchmark with a vector field on a curved surface" width="32%" align="middle"/>
</p>

<!-- ![](../images/surface_GL.mp4) -->

### A domain decomposition method for waveguide circuits
I have demonstrated how a complicated photonic circuit can be efficiently be simulated by recursively merging impedance to impedance maps for individual circuit elements. When circuit elements are connected by straight pipes, these maps can be greatly compressed by projecting the impedance data onto the modes for each pipe, resulting in an efficient numerical solver.

<!--- <img src="https://github.com/user-attachments/assets/d30d5f61-250d-490f-8f79-ed0d7a55717f" width="40%" />-->
<img src="{{ site.baseurl }}/images/quilt_ex.png" alt="Wave field in a quilt-like waveguide circuit" width="40%" />
