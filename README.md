# CIM_for_learning
Personal project to learn more about Coherent Ising Machines and mixed signal design

## Description
This is a personal project to get more familiar with mixed signal design on a CMOS chip. Coherent Ising Machines are physical systems (analog computers) to solve NP complete optimization problems.

## Why is it relevant?
Moore's law is coming to an end as production processes come to the physical limit where quantum effects dominate. These quantum effects (like quantum tunneling) are unwanted in a digital chip because it hinders the control of separating currents to create zeroes and ones. The current trend goes into several directions.
* Accept loss of part of the chips
* Use specialized chips for different algorithms and mathematical problems. This includes TPUs (Tensor Product Units), GPUs (Graphical Processing Units) and QPUs (Quantum Processing Units or short quantum computers).
* Use analog computers. There are several types such as photonic computers, old electrical analog computers (like in the 1950s before digital computers were even a thing, but much smaller) and analog quantum computers.

* Another aspect is the fact that digital processors need a lot of energy. Certain types of analog computers can use the physical time evolution and thus only take up a small part of the energy compared to digital computers. This applies mostly to electronic analog computers. I'm not sure about photonic computing but at least most quantum computers take up a lot of energy for control and cooling. Analog computers - CIM and others - are also much cheaper to build.

### Why CIM?
All NP complete optimization problems (use cases such as traffic optimization or portfolio optimization) can be mapped to the Ising Hamiltonian, a model from solid state physics to describe magnetism. All attacks on post quantum cryptography by quantum scientists also use the Ising model to map out their attacks.
