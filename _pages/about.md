---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a William H. Kruskal Instructor in the Committee for Computational and Applied Mathematics in the Department of Statistics at the University of Chicago. My research uses the tools of numerical analysis and applied analysis to develop new fast algorithms for numerically solving PDEs. My recent work includes a new integral equation method for solving elliptic PDEs on surfaces, new integral equation methods for scattering problems involving unbounded interfaces, and a study of the regularity of PDEs on surfaces with edges and corners.



## Research Projects


### Scattering problems in unbounded interfaces
I have developed a method for solving a class of decomposable scattering scattering problems involving unbounded interfaces. If the computational domain can be split into simple subdomains (such as straight waveguides or periodic gratings), then the domain Green's functions for each piece can be used to reduce the scattering problem to an integral equation on the domain boundaries. The resulting integral equation can then be analytically continued to the complex plane, where it can be safely truncated and discretized using standard integral equation techniques.

![Waveguide splitters](../images/egg_soln.pdf) ![Matched gratings](Matched_q_per.pdf) ![Matched gratings](https://github.com/user-attachments/files/18774619/Matched_q_per.pdf)


### A fast solver for surface PDEs
PDEs on surfaces occur in a wide variety of applications.    
![Surface Ginzburg-Landau equation](../images/surface_GL.mp4)

### A domain decomposition method for waveguide circuits

## Publications
Goodwill, T. and Epstein, C. *A numerical method for scattering problems with unbounded interfaces.* Preprint [arXiv 2411.11204](https://arxiv.org/pdf/2411.11204).

Goodwill, T. and O'Neil, M. A parametrix method for elliptic surface PDEs. Accepted by Pure and Applied Analysis, 2025. [arXiv link](https://arxiv.org/pdf/2401.12501)

Goodwill, T. and O'Neil, M. An interface formulation of the Laplace-Beltrami problem on piecewise smooth surfaces. SIAM Journal on Mathematical Analysis 55(6), 2023. [arXiv link](https://arxiv.org/pdf/2108.08959)

Li, H., Goodwill, T., Wang, Z. J., and Ristroph, L. *Centre of mass location, flight modes, stability and dynamic modelling of gliders.* Journal of Fluid Mechanics, 937, 2022.

Morsy-Osman, M., Sowailem, M., El-Fiky, E., Goodwill, T., Hoang, T., Lessard, S., and Plant, D. V. *DSP-free coherent-lite transceiver for next generation single wavelength optical intra-datacenter interconnects.* Optics Express, 26(7), 2018.


## Software
**ChunkIE A Matlab integral equation toolbox** &mdash; A MATLAB toolbox for solving boundary integral equations in 2D.

**fmm3dbie** &mdash; A package for solving boundary integral equations in 3D. Callable from Fortran and MATLAB.
