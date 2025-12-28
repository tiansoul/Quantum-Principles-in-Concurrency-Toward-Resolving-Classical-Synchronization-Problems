# Quantum Principles in Concurrency: Toward Resolving Classical Synchronization Problems

This repository hosts the official implementation of **Quantum Principles in Concurrency: Toward Resolving Classical Synchronization Problems**.

## Paper Status

📌 **Manuscript status:** *Accepted*  
📌 **Target journal:** *KSII Transactions on Internet and Information Systems*  
📌 **Code release:** The **full simulation code** released.

## Abstract
This paper investigates the application of quantum principles – most notably superposition and entanglement – to reframe classical concurrency problems in software engineering. While other research has explored quantum concepts primarily as tools for parallelization, this work advances the discourse by proposing quantum-inspired abstractions for reasoning about mutual exclusion, race conditions, deadlocks, and the producer–consumer problem. By treating threads and shared resources as qubits and modeling their interactions via correlated quantum states within an abstract state-space, we present a framework that illustrates how quantum formalisms can conceptually model concurrency patterns, supported by mathematical formulations in Dirac notation and circuit representations. Superposition naturally models multiple execution paths, while entanglement provides symbolic global correlations rather than operational synchronization, offering new perspectives on long-standing concurrency challenges. Our simulations across four scenarios demonstrate that these quantum-inspired formulations can highlight order-sensitivity and contention patterns in a unified mathematical setting. These results do not constitute practical concurrency mechanisms, but they suggest how quantum principles may inform future hybrid quantum–classical analysis tools. We also conclude with a discussion on potential integration into hybrid systems, highlighting both practical benefits and open challenges.

## Citation

If you find this work helpful, please cite our paper (BibTeX will be provided after publication).

```bibtex
@article{liqconcurrency2025,
  title   = {Quantum Principles in Concurrency: Toward Resolving Classical Synchronization Problems},
  author  = {Yuanjie Li, Jinsuk Baek, Minho Jo*},
  journal = {KSII Transactions on Internet and Information Systems},
  year    = {2026},
  note    = {Accepted}
}
