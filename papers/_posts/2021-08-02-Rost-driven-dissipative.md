---
layout  : paper
title   : Demonstrating robust simulation of driven-dissipative problems on near-term quantum computers
authors : Rost B, Del Re L, Earnest N, Kemper AF, Jones B, Freericks JK
year    : 2021
ref     : "B. Rost et al., arXiv:2108.01183"
journal : arXiv:2108.01183
arxiv   : 2108.01183
image   : /images/papers/rost_driven_dissipative.png
ncsu    : True
---

# Abstract
Quantum computers are poised to revolutionize the simulation of quantum-mechanical systems in physics and chemistry. Current quantum computers execute their algorithms imperfectly, due to uncorrected noise, gate errors, and decoherence. This severely limits the size and scope of protocols which can be run on near-term quantum hardware. Much research has been focused on building more robust hardware to address this issue, however the advantages of more robust algorithms remains largely unexplored. Here we show that algorithms for solving the driven-dissipative many-body problem, among the hardest problems in quantum mechanics, are inherently robust against errors. We find it is possible to solve dissipative problems requiring deep circuits on current quantum devices due to the contractive nature of their time evolution maps. We simulate one thousand steps of time evolution for the non-interacting limit of the infinite driven-dissipative Hubbard model, calculate the current through the system and prepare a thermal state of the atomic limit of the Hubbard model. These problems were solved using circuits containing up to two thousand entangling gates on quantum computers made available by IBM, showing no signs of decreasing fidelity at long times. Our results demonstrate that algorithms for simulating dissipative problems are able to far out-perform similarly complex non-dissipative algorithms on noisy hardware. Our two algorithmic primitives are the basic building blocks of many condensed-matter-physics systems, and we anticipate their demonstrated robustness to hold when generalized to solve the full many-body driven-dissipative quantum problem. Building upon the algorithms presented here may prove to be the most promising approach to tackle important, classically intractable problems on quantum computers before error correction is available. 
