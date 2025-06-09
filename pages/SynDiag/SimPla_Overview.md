---
layout: splash
title: SynDiag - Simulated Plasma
math: true
permalink: /SynDiag_Overview/
sidebar: 
  nav:  "docs"
---

<script type="text/javascript" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>


# About SynDiag

**SynDiag (Synthetic Diagnostics)** is a module designed to simulate various tokamak diagnostics in a modular way. Each diagnostic technique is implemented as a separate class, enabling flexible and detailed synthetic data generation for experimental comparison and validation.

The module consists of classes representing the following diagnostics:

- **PickUpCoils**: Simulates the magnetic signals measured by pickup coils placed around the tokamak.
- **SaddleCoils**: Models the magnetic response detected by saddle coils, which are sensitive to poloidal magnetic flux.
- **FluxLoops**: Represents flux loops that measure the poloidal magnetic flux linked to plasma currents.
- **ThomsonScattering**: Simulates the electron temperature and density measurements obtained via Thomson scattering diagnostics.
- **InterferometerPolarimeter**: Models interferometer and polarimeter diagnostics used for measuring line-integrated electron density and magnetic field effects.

Each class encapsulates the physics and signal processing relevant to its respective diagnostic, allowing for comprehensive synthetic diagnostic simulations within the tokamak environment.


