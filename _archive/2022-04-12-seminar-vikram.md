---
title: "Towards Large-scale Quantum Accuracy Materials Simulations (12/04/22)"
permalink: /seminar/vikram-12-apr-2022
---

### Speaker and Affliation:
Vikram Gavini<br>
Department of Mechanical Engineering,<br> Department of Materials Science and Engineering,<br> University of Michigan, Ann Arbor

### When?
12<sup>th</sup> April, 2022 (Tuesday), 10:00 AM (India Standard Time)

### Location
Department of Materials Engineering, KPA auditorium

### Abstract
Electronic structure calculations, especially those using density functional theory (DFT), have been very useful in understanding and predicting a wide range of materials properties. The importance of DFT calculations to engineering and physical sciences is evident from the fact that ~20% of computational resources on some of the world’s largest public supercomputers are devoted to DFT calculations. Despite the wide adoption of DFT, and the tremendous progress in theory and numerical methods over the decades, the following challenges remain. Firstly, the state-of-the-art implementations of DFT suffer from cell-size and geometry limitations, with the widely used codes in solid state physics being limited to periodic geometries and typical simulation domains containing a few hundred atoms. This limits the complexity of materials systems that can be treated using DFT calculations. Secondly, there are many materials systems (such as strongly-correlated systems) for which the widely used model exchange-correlation functionals in DFT, which account for the many-body quantum mechanical interactions between electrons, are not satisfactory. Addressing these challenges will enable large-scale quantum-accuracy DFT calculations, and can significantly advance our ab initio modeling capabilities to treat complex materials systems.

This talk will discuss our recent advances towards addressing the aforementioned challenges. In particular, the development of computational methods and numerical algorithms for conducting fast and accurate large-scale DFT calculations using adaptive finite-element discretization will be presented, which form the basis for the open-source DFT-FE code. The computational efficiency, scalability and performance of DFT-FE will be presented, which demonstrates a significant outperformance of widely used plane-wave DFT codes. Some recent studies that highlight the capabilities of DFT-FE will be presented, which include: (i) studies on dislocation energetics in Magnesium; (ii) understanding the electronic structure underpinnings of electron transport in DNA molecules. In addressing the second challenge, our recent breakthrough in accurately solving the inverse DFT problem will be presented, which has enabled the computation of exact exchange-correlation potentials for polyatomic systems. Ongoing efforts on using the exact exchange-correlation potentials to develop a data-driven approach for improving the exchange-correlation functional description in DFT will be discussed.

This is joint work with Sambit Das (U. Michigan), Bikash Kanungo (U. Michigan) and Phani Motamarri (IISc).
 