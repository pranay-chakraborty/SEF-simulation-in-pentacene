**Timeline of the project**

Quantum Mechanical Modeling of Singlet Fission in Pentacene Crystals: Thorough Structural Analysis, Scalable Hamiltonian Modeling, Eigenstates Characterization, and Simulation of Absorption Spectrum.

- **Basics:** To begin with, I read relevant portions from [Casanova's paper](https://doi.org/10.1021/acs.chemrev.7b00601) on theoretical modeling of singlet exciton fission, to gain a footing in the topic. More importantly, I gained knowledge of the basis states that shall be used to construct the Hamiltonian, their significance etc.

- **Exercises:** As an exercise, I developed Julia scripts to model Hamiltonians and simulate absorption spectra for linear N-aggregates (N = 2,3,4) and an SEF Dimer. (All my later codes were automated, the same code could generate different scenarios). This gave me insight into modeling (scalable) diabatic Hamiltonians, and translating 3D spatial orientation data of the transition dipole moments of the system into code.

- **Results:** I mostly referred to [Reichmann et al.'s papers](https://doi.org/10.1063/1.4982362). I analysed the N×N crystal structure thoroughly, developed the code to store/manipulate the data of all the transition dipole moments of the entire structure, in a scalable manner. Then I designed a scalable Hamiltonian for the same N×N crystal structure. Thus, I was finally able to simulate the absorption spectrum of the system. I obtained the character plots of the eigen-states after performing eigenstate characterizations, which gave insight into the contribution of each basis state into each eigen-energies and how the relative contributions changed across the spectrum. **All codes were written in Julia.**
