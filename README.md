# Cross-Resonance-Numerics
A Python (QuTiP) based simulation to quantify cross resonance gate infidelity. This has a general Python Class to simulate cross resonance gates between any two qubits in an arbitrary quantum processor. The Class has methods to extract gate infidelity and quantify error due to leakage and due to imperfect rotation. The Jupyter Notebook has details written inside. Documentation is still ongoing.

Examples of results replicated `[1`]/produced from the simulations:

![CNOT Time Calibration](/plots/CNOT_time_2_Qubit.jpeg)

A plot of time taken to create an angle of $\pi$ between the target's final states, when the control is in $|0>$ vs $|1>$

References:
1. [Sumeru Hazra et al. - Phys. Rev. Applied 16, 024018 – Published 11 August 2021](https://journals.aps.org/prapplied/abstract/10.1103/PhysRevApplied.16.024018)
2. [Vinay Tripathi et al. - Phys. Rev. A 100, 012301 – Published 1 July 2019](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.100.012301)
