---
title: "First release of phase-field software 'Microsim'"
header:
 image: /assets/images/slider/microsim_lab.png
 teaser: /assets/images/slider/microsim_lab.png
permalink: /highlights/microsim-lab
---
"MicroSim" is a project under the <a href="https://www.nsmindia.in/" target="_blank">National Supercomputing Mission, Govt of India</a>. The project offers a set of codes that can use high performance computing to simulate microstructure evolution using the Phase Field technique. MicroSim is a software stack that consists of phase-field codes that offer flexibility with discretization, models as well as the high-performance computing hardware (CPU/GPU) that they can execute on. Along with this the stack also consists of Multi-physics solver modules that are based on OpenFoam and AMRex libraries(will be added soon). The stack has an integrator interface that is built using python that allows one to create the input and filling files required for the solvers as well as provides a consolidated framework to choose the solver, compile, execute and visualize simulation results. The project is a consortium between (IISc Bangalore, IIT Hyderabad, IIT Bombay, IIT Madras, Savitribai Phule Pune University, C-DAC Pune). The phase-field models include the Grand-potential formalism, Kim-Kim Suzuki as well as the Cahn-Hilliard descriptions. The discretizations include FDM, FVM and FFT. The first release of the software contains modules for the simulation of microstructure evolution during solidification and precipitation. Future releases will include modules on grain-growth and recrystallization. Following are the links to the software on GitHub and MicroSim has been released with a GNU-GPLv3 license.

## Links to MicroSim
<a href="https://github.com/ICME-India/MicroSim/releases/tag/v1.0.2" target="_blank">MicroSim release (version 1.0.2)</a>

<a href="https://github.com/ICME-India/MicroSim" target="_blank">MicroSim repository</a>

## Contributors

* OpenFoam solvers and Documentation: Tanmay Dutta, Ravi Kumar, Birkamjit Karmakar, Umate Kartik (IISc)
* Python wrapper and infile generator: Ajay Sagar (IISc)
* KKS OpenCI and FFTW codes: Dasari Mohan, M.P. Gururajan, Gandham Phanikumar (IIT Bombay, IIT Madras)
* KKS Nvidia-CUDA: Saurav Shenoy, Pankaj, and Saswata Bhattacharyya (IIT Hyderabad)
* Grand-potential-based solvers: Abhik Choudhury (IISc)

## Acknowledgments

* Sumeet Rajesh Khanna (PhD, IISc)
* Tushar Jogi (PhD, IIT Hyderabad)
* Gerald Tennyson (PhD, IIT Madras)
* Ravi Kumar Singh (M. Tech., IISc)
* Umate Kartik (BS, IISc)
* Bikramjit Karmakar (BS/MS, IISc)


