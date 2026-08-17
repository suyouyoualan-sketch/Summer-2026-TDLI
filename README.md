# Summer-2026-TDLI
My summer research at Tsung-Dao Lee Institute, Shanghai Jiao Tong University in summer 2026

# Electrothermal Manipulation of Abrikosov Vortices via Localized Heating

Summer Research 2026 @ Tsung-Dao Lee Institute (TDLI)  
Supervisor: Assoc. Prof. Liu Liang

## Overview

Abrikosov vortices in topological superconductors may host Majorana zero modes, making controlled vortex manipulation relevant to potential braiding-based quantum computation. This project investigates whether **localized electrothermal heating** can provide a controllable mechanism for manipulating vortex motion. fileciteturn1file0L8-L18

A two-dimensional overdamped vortex-dynamics model was developed in which localized heating generates temperature gradients that exert effective thermal forces on vortices. The model additionally incorporates vortex–vortex interactions and pinning effects. fileciteturn1file0L36-L38 fileciteturn1file0L58-L88

## Project Goals

The project investigates three main questions:

- Can a localized hotspot capture an Abrikosov vortex?
- Can controlled heating transfer a vortex between two hotspots?
- Can multiple programmable hotspots guide a vortex along a prescribed trajectory? fileciteturn1file0L19-L25

## Model

Localized heating is approximated using Gaussian temperature profiles. The resulting temperature gradient generates an effective thermal driving force,

\[
\mathbf{f}_T = \alpha_T \nabla T.
\]

Assuming strongly dissipative vortex dynamics, the motion is modeled in the overdamped regime as

\[
\eta \frac{d\mathbf r}{dt}
=
\mathbf f_T+\mathbf f_{\mathrm{pin}}+\mathbf f_{\mathrm{vv}},
\]

where the additional terms describe pinning and vortex–vortex interactions. fileciteturn1file0L39-L68

## Numerical Results

Numerical simulations demonstrate that a single localized hotspot can capture a vortex, with stronger heating increasing the effective capture radius. By dynamically decreasing the temperature of one hotspot while increasing that of another, controlled vortex transfer between electrodes can also be achieved. The transfer behavior depends on parameters including heating strength, hotspot separation, and switching time. fileciteturn1file0L89-L109

Extending this idea to multiple sequentially activated hotspots enables programmable vortex trajectories. In particular, a circular array of 16 hotspots was used to demonstrate controlled circular vortex motion. fileciteturn1file0L110-L136

## Key Outcomes

- Developed a two-dimensional overdamped model of electrothermally driven vortex dynamics.
- Demonstrated vortex capture and controlled transfer through localized heating.
- Investigated the parameter dependence of successful vortex transfer.
- Demonstrated programmable circular vortex motion using sequentially activated hotspots.
- Established localized electrothermal control as a possible approach toward programmable manipulation of superconducting vortices. fileciteturn1file0L137-L151

## Future Directions

Possible extensions include solving a more realistic heat-diffusion equation, incorporating stronger pinning effects, and comparing the model quantitatively with experimental parameters. fileciteturn1file0L148-L151
