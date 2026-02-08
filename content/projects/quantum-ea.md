---
title: "Quantum Computing Evolutionary Algorithm Design"
date: 2026-02-08
description: "Open-source framework for automatic quantum circuit discovery using evolutionary algorithms, NSGA-II, MAP-Elites, and deep learning. Pure numpy simulation, 6 optimisers, 6 quantum problems."
tags: ["quantum computing", "evolutionary algorithms", "open source", "python"]
author: "Thomas Snell"
showtoc: false
---

An open-source framework that automatically discovers quantum algorithms using six different optimisation methods, benchmarked across six quantum problems.

## Highlights

- **6 optimisers**: EA, Random Search, Gradient, REINFORCE, NSGA-II, MAP-Elites
- **6 quantum problems**: Grover, Flip, Inverse, Fourier, Deutsch--Jozsa, Bernstein--Vazirani
- **Fast simulation**: Pure numpy statevector simulator (~microseconds per evaluation), 100--1000x faster than Qiskit
- **Quality-diversity**: MAP-Elites discovers diverse circuit families with 79--87% archive coverage
- **Reproducible**: Deterministic seeds, automated study scripts, 360 experiments

## Links

- [GitHub Repository](https://github.com/llens/QuantumComputingEvolutionaryAlgorithmDesign)
- [Paper (PDF)](https://github.com/llens/QuantumComputingEvolutionaryAlgorithmDesign/blob/master/paper/paper.pdf)
- [Blog Post: How I used MAP-Elites to discover diverse quantum circuits](/posts/quantum-circuit-qd-optimization/)
