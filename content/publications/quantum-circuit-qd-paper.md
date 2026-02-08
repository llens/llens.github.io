---
title: "Multi-Objective and Quality-Diversity Optimization of Quantum Circuits via Statevector Simulation"
date: 2026-02-08
description: "Research paper benchmarking 6 optimisation methods (EA, Random Search, Gradient, REINFORCE, NSGA-II, MAP-Elites) across 6 quantum problems. Among the first applications of MAP-Elites to quantum circuit discovery."
tags: ["quantum computing", "evolutionary algorithms", "MAP-Elites", "NSGA-II", "quality-diversity", "multi-objective optimisation"]
author: "Thomas Snell"
showtoc: false
---

**Thomas Snell** (2026)

## Abstract

We present a comparative study of six optimisation methods for automatic quantum circuit synthesis: evolutionary algorithm, random search, gradient-based continuous relaxation, REINFORCE policy gradient, NSGA-II multi-objective search, and MAP-Elites quality-diversity optimisation. Using a pure numpy statevector simulator (100--1000x faster than Qiskit), we benchmark these methods across six quantum problems (Grover, Flip, Inverse, Fourier, Deutsch--Jozsa, Bernstein--Vazirani) with 3-qubit circuits and a 10,000-evaluation budget.

MAP-Elites achieves 79--87% archive coverage across problems, discovering diverse families of high-fitness circuits indexed by active depth and entanglement density. NSGA-II produces the most compact circuits (2.6--11.1 non-identity gates) via Pareto-front selection on fidelity, depth, and gate count.

## Links

- [Paper (PDF)](https://github.com/llens/QuantumComputingEvolutionaryAlgorithmDesign/blob/master/paper/paper.pdf)
- [Code & Data](https://github.com/llens/QuantumComputingEvolutionaryAlgorithmDesign)
- [Literature Review (PDF)](https://github.com/llens/QuantumComputingEvolutionaryAlgorithmDesign/blob/master/literature_review/literature_review.pdf)

## Citation

```
Snell, T. (2026). Multi-Objective and Quality-Diversity Optimization
of Quantum Circuits via Statevector Simulation. Quantum Computing
Evolutionary Algorithm Design.
```
