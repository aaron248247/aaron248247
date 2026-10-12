# Computational Physics & Engineering

I'm a quantitative analyst with graduate training in physics. My interests are in computational electromagnetics, photonics, and radar signal processing.

I enjoy working through the physics behind a problem, building a numerical model, and checking whether the results agree with what theory predicts. The projects below reflect that approach, with an emphasis on verification, convergence, and understanding the limitations of the models.

## Projects

### 1. [Photonic-Crystal True-Time-Delay Beamforming](https://github.com/aaron248247/pc-ttd-beamforming)

This project investigates W1 photonic-crystal waveguides as potential delay elements for phased-array beamforming.

It uses MEEP and MPB to study electromagnetic propagation and dispersion, then connects the calculated delays to phased-array steering behavior. The repository includes numerical verification, simulation results, and array-level analysis.

**Topics:** Photonic crystals, FDTD, dispersion, group delay, phased arrays.

### 2. [Electromagnetic Scattering and Periodic Structures](https://github.com/aaron248247/computational-em-scattering-lab)

This project started with a straightforward question: how accurately can an FDTD simulation reproduce the analytical scattering solution for a dielectric cylinder?

The first part compares numerical results against Mie theory and examines convergence. The second extends the model to a periodic array of dielectric cylinders, studying how lattice spacing, polarization, and incidence angle affect the electromagnetic response.

**Topics:** Maxwell's equations, Mie scattering, FDTD, resonances, periodic structures.

### 3. [Array Signal Processing and Radar Simulation](https://github.com/aaron248247/array-signal-processing-lab)

This project explores several methods used in antenna arrays and radar processing.

It includes conventional and MVDR beamforming, covariance estimation, jammer suppression, pulse compression, Doppler processing, and CFAR detection. The experiments examine performance under different conditions, including steering errors and interference.

**Topics:** Array processing, adaptive beamforming, radar, detection theory, numerical simulation.

## Tools and Methods

Most of my computational work uses Python, NumPy, SciPy, and scientific visualization tools. For electromagnetic simulations, I use MEEP and MPB.

Across these projects, I focus on:

- Comparing numerical calculations with analytical results where possible.
- Checking convergence and sensitivity to numerical parameters.
- Testing how models behave when assumptions or operating conditions change.
- Keeping the code, results, and documentation organized so experiments can be reproduced.

Each repository contains more detail about its numerical methods, results, and limitations.
