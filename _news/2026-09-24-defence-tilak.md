---
title: "Mtech Thesis Defence: Mr. Tilak Raj Pant (24/09/26)"
permalink: /defence/tilak-24-sep-2026
---
### Thesis title:
A Fourier-Based Electrostatic Module for DAMASK: Numerical Analysis, Validation, and Microstructural Applications

### Faculty advisor(s):
Prof. Praveen Kumar 

### When?
24<sup>th</sup> September, 2026 (Thursday), 04:30 PM (India Standard Time)

### Mode
Online

https://teams.microsoft.com/meet/426547913541796?p=q60idqw1mdjYD69a1g

### Abstract
Electropulsing treatment, the passage of short high-density electric current pulses through a metal, is a versatile route to microstructure modification and improved formability in lightweight hexagonal alloys such as AZ31 magnesium. Its effects arise from a combination of Joule heating, paramagnetic de-pinning of dislocations, and the athermal electron-wind force, all of which depend on the local current density. Every existing crystal-plasticity model of electroplasticity, however, represents this current density as a single spatially uniform scalar, whereas in a real polycrystal the orientation-dependent conductivity tensor makes it vary in both magnitude and direction from grain to grain. Resolving these mechanisms at the grain scale therefore requires the full vector current-density field at every microstructural point---a field unavailable to existing models.

This thesis develops the missing computational infrastructure: a spectral electrostatic solver for quasi-static charge conduction in heterogeneous periodic media, integrated into the crystal-plasticity framework DAMASK. The quasi-static charge-conservation equation is recast as a Lippmann--Schwinger integral equation through a polarisation-field splitting, yielding a closed-form Green's operator solved by Fast Fourier Transforms. A systematic study of six differentiation operators establishes that the effective wavenumber, rather than the formal order, governs solver behaviour, and yields contrast-dependent operator-selection guidelines: second-derivative schemes for accuracy in smooth media, and the robust first-derivative second-order scheme for high-contrast defects. The solver is verified against analytical and finite-element solutions, and its electro-thermal coupling is exercised on an instrumented electropulsing experiment, the reduced thermal model being calibrated against the infrared temperature record and the coupled solution then compared with it.

In polycrystalline AZ31, grain-resolved anisotropic current density is computed; a critical RVE length-scale criterion specific to electro-thermal simulation is established; and the deformation-driving internal stress is shown to originate not in local Joule hotspots but in the anisotropic thermal expansion of the textured lattice---a prediction supported by cryogenic EBSD evidence of tensile twinning. The work thus supplies the grain-resolved current density that spatially resolved electroplasticity simulations have hitherto lacked, together with a first application exercising its thermal pathway; the athermal mechanisms the infrastructure is built to serve remain for future work.