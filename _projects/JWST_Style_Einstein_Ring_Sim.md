---
layout: page
title: Einstein Ring Gravitational Lensing Simulation
description: Advanced physics-informed Python pipeline simulating strong gravitational lensing, forward-modeling cosmic geometry, ray-tracing, and JWST-style NIRCam optics.
importance: 1
category: "Physics & Complex Systems"
github: https://github.com/Pablo-Santana-MX/jwst-einstein-ring-simulation
img: assets/img/einstein_ring_thumb.jpg
---

<div align="center">
  <a href="https://github.com/Pablo-Santana-MX/jwst-einstein-ring-simulation">
    <img src="https://img.shields.io/badge/GitHub-Repository_&_Code-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repository" />
  </a>
  <img src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SciPy-FFT_Convolution-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" alt="SciPy" />
  <img src="https://img.shields.io/badge/Lenstronomy-SIE_Physics-2b2d42?style=for-the-badge&logo=python&logoColor=white" alt="Lenstronomy" />

  <br><br>
  <img src="assets/img/jwst_einstein_ring_preview.png" width="900" alt="Synthetic Einstein Ring Preview" />
  <p><em>Rendered preview: Synthetic JWST/NIRCam multiband composite showing the "Cosmic Horseshoe" strong lensing configuration.</em></p>
</div>

## 🌌 Visualizing Cosmic Spacetime Curvature
Data science and computational modeling extend far beyond conventional business analytics. This project implements a rigorous, physics-informed forward-modeling pipeline to simulate strong gravitational lensing—mapping how massive foreground galaxy clusters warp space-time to stretch distant background galaxies into striking Einstein rings and cosmic horseshoes.

## 🧠 Architecture & Methodology
- **Ray-Shooting & Lensing Physics:** Leveraging advanced astrophysical libraries (`lenstronomy`) to compute non-linear Singular Isothermal Ellipsoid (SIE) deflection fields and external shear tensors.
- **Signal Processing & Optics:** Applying Fast Fourier Transform (FFT) convolutions via `scipy` to integrate instrument-specific Point Spread Functions (PSFs) and emulating realistic sensor noise (Poisson shot noise and Gaussian read noise).
- **High-Dynamic-Range Rendering:** Using custom multiband synthesis (F115W, F200W, F444W NIRCam-inspired bands) combined with inverse hyperbolic sine (`asinh`) stretching for cinematic RGB visualization.

## 📈 Analytical Impact & Codebase
Building computational astrophysics pipelines demonstrates advanced mathematical abstraction, proving that high-performance vectorization, numerical optimization, and complex spatial modeling translate seamlessly into rigorous problem-solving and state-of-the-art scientific visualization.

Explore the complete source code, reproducible environment configuration, and automated alignment animation tools directly in the [GitHub Repository](https://github.com/Pablo-Santana-MX/jwst-einstein-ring-simulation).
