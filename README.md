# Cross-Resonance-Numerics
A Python (QuTiP) based simulation to quantify cross resonance gate infidelity. This has a general Python Class to simulate cross resonance gates between any two qubits in an arbitrary quantum processor. The simulation does not have decoherence. The Class has methods to extract gate infidelity and quantify error due to leakage and due to imperfect rotation. The Jupyter Notebook has details written inside. Documentation is still ongoing.

Examples of results replicated [1]/produced from the simulations:

<img src = "/Plots/CNOT_time_2_Qubit.jpeg" width = "400" height = "300" />

A plot of time taken to create a 180 degree separation between target states, conditional on control state. 

<img src = "/Plots/Error_Budget_2_Qubit_70_MHz.jpeg" width = "600" height = "300" />

A plot of Gate infidelity and it's components vs drive amplitude, for a two qubit setup

<img src = "/Plots/Spec_sweep_70_MHz_Ctrl_Tgt.png" width = "600" height = "300" />

<img src = "/Plots/Spec_sweep_Error_Budget.png" width = "700" height = "350" />

A plot of gate infidelity and it's components. vs spectator-control detuning, where the spectator and target are coupled to the control qubit. We can identify bands of frequency where it is ideal to place the spectator. The expected poles for multiphoton processes show up as peaks.

References:
1. [Sumeru Hazra et al. - Phys. Rev. Applied 16, 024018 – Published 11 August 2021](https://journals.aps.org/prapplied/abstract/10.1103/PhysRevApplied.16.024018)
2. [Vinay Tripathi et al. - Phys. Rev. A 100, 012301 – Published 1 July 2019](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.100.012301)
