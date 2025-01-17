---
layout  : paper
title   : Simulating the Mott transition on a noisy digital quantum computer via Cartan-based fast-forwarding circuits
authors : Steckmann T, Keen T, Kemper AF, Dumitrescu EF, Wang Y
year    : 2021
ref     : "T. Steckmann et al., arXiv:2112.05688"
journal : arXiv:2112.05688
arxiv   : 2112.05688
image   : /images/papers/steckmann_dmft_phase_diagram.jpg
ncsu    : True
---

# Abstract
Dynamical mean-field theory (DMFT) maps the local Green's function of the Hubbard model to that of the Anderson impurity model and thus gives an approximate solution of the Hubbard model by solving the simpler quantum impurity model. Quantum and hybrid quantum-classical algorithms have been proposed to efficiently solve impurity models by preparing and evolving the ground state under the impurity Hamiltonian on a quantum computer instead of using intractable classical algorithms. We propose a highly optimized fast-forwarding quantum circuit to significantly improve quantum algorithms for the minimal DMFT problem preserving the Mott phase transition. Our Cartan decomposition based algorithm uses a fixed depth quantum circuit to eliminate time-discretization errors and evolve the initial state over arbitrary times. Exploiting the structure of the fast-forwarding circuits, we sufficiently reduce the gate cost to simulate the dynamics of, and extract frequencies from, the Anderson impurity model on noisy quantum hardware and demonstrate the Mott transition by mapping the phase-diagram of the corresponding impurity problem. Especially near the Mott phase transition when the quasiparticle resonance frequency converges to zero and evolving the system over long-time scales is necessary, our method maintains accuracy where Trotter error would otherwise dominate. This work presents the first computation of the Mott phase transition using noisy digital quantum hardware, made viable by a highly optimized computation in terms of gate depth, simulation error, and run-time on quantum hardware. The combination of algebraic circuit decompositions and model specific error mitigation techniques used may have applications extending beyond our use case to solving correlated electronic phenomena on noisy quantum computers. 
