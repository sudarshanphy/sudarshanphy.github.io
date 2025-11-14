---
title: "2D Wave equation solver with MPI and HDF5"
description: "A parallelized finite-difference solver for the 2D wave equation equation using MPI domain decomposition and HDF5 for output."
thumbnail: /images/themes/homepage-light.png
layout: single
author_profile: true
order: 1
---

<img src="/images/themes/homepage-light.png" class="project-thumb">

### Overview

This project implements a 2D advection-diffusion solver using second-order finite differences and MPI-based domain decomposition. The simulation domain is split across distributed-memory ranks, with ghost-cell synchronization at each time step. This work is based on ...

### Features

- MPI parallelization
- 2D Laplacian stencil
- Ghost exchange via `MPI_Sendrecv`
- Visualized using Matplotlib / ffmpeg

### Example Output

**Movie of a Gaussian blob diffusing:**

<!--
<video width="100%" controls>
  <source src="/images/projects/diffusion_movie.mp4" type="video/mp4">
</video>
-->

