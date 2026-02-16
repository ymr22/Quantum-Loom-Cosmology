# The Quantum Loom: A Computational Refutation of the Big Bang Singularity

**Author:** Yağmur Üstel 

**Hardware:** IBM Quantum `ibm_marrakesh` (156-Qubit Heron Processor)

## 🌌 Overview
This repository contains the experimental data and code for the paper **"The Superfluid Universe: A Unified Topological Resolution to Dark Energy, The Hubble Tension, and the Singularity"**

We demonstrate that Spacetime is not a continuous manifold, but a **Discrete Topological Superfluid**. By mapping cosmological parameters onto a superconducting qubit lattice, we simulated the hydrodynamic evolution of the universe and resolved six major cosmological phenomena.

## 🧪 The Experiments
Click on the notebooks below to view the simulation code and results:

### 1. [The Hubble Tension (Viscosity)](./01_Hubble_Tension_Viscosity.ipynb)
**Result:** We detected a relaxation in vacuum viscosity. The "Stiff" early vacuum ($H_0 \approx 93.3$) vs. the "Loose" late vacuum ($H_0 \approx 98.9$) yields a tension of **$\Delta H_0 \approx 5.6$ km/s/Mpc**, resolving the discrepancy without modifying ΛCDM.

### 2. [Dark Energy (Hydraulic Pressure)](./02_Dark_Energy_Hydraulics.ipynb)
**Result:** We identified that cosmic acceleration is driven by the entropic displacement of the vacuum. The measured Cosmological Coupling of **$k \approx 1.78$** confirms the Holographic Scaling Law ($k \approx 2$).

### 3. [Black Hole Teleportation (Unitarity)](./03_Black_Hole_Teleportation.ipynb)
**Result:** An entanglement swapping protocol across the horizon yielded a fidelity of **$69.3\%$** (Quantum Channel Strength: $38.6\%$). This confirms "Information Leakage" via traversable ER=EPR bridges.

### 4. [The Singularity Refutation (Jamming)](./04_Black_Hole_Jamming.ipynb)
**Result:** We discovered a "Jamming Transition" at the Planck density limit ($\rho \approx 2\pi$). Vacuum mobility drops to **$M = 0.000$**, proving that gravitational collapse results in a **Topological Solid (Planck Star)** rather than a mathematical singularity.

### 5. [Primordial B-Modes](./05_Primordial_B_Modes.ipynb)
**Result:** The "Freezing" phase transition of the early vacuum generated a strong **$52.1\%$ Tensor-mode signal** (vs. $17.5\%$ for Scalar models). This confirms that B-modes are topological defects arising from a parity-violating phase twist.

### 6. [Solar System Resonance (Lagrange)](./06_Solar_System_Resonance.ipynb)
**Result:** We successfully reproduced the stability of **Trojan Asteroids ($L_4/L_5$)** with $>98\%$ stability, confirming that celestial bodies accumulate at vacuum standing-wave nodes.

### 7. [Multi-Body Stability (Saturn-Jupiter)](./07_Multi_Body_Saturn.ipynb)
**Result:** We mapped the radial stability of the Asteroid Belt, identifying the **3.35 AU Hecuba Gap** as a vacuum instability zone (**$2\%$ stability**) caused by the Saturn-Jupiter resonance alliance.

## ⚙️ How to Reproduce
1. Install requirements: `pip install qiskit qiskit-ibm-runtime numpy matplotlib`
2. Open any `.ipynb` file in Jupyter or VS Code.
3. Insert your IBM Quantum Token.
4. Run the cells to simulate the universe.

## License
MIT License
