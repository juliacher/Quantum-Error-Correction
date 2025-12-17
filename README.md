# Quantum Error Correction — 3-Qubit Repetition Code

This repository contains a simulation and analysis of the **3-qubit repetition code**, a simple quantum error-correcting code that protects a single logical qubit against **bit-flip errors**. The project implements the full encode–noise–correct–decode cycle and evaluates the resulting **logical error probability** as a function of the physical error rate.

---

## Project Overview

The project demonstrates how redundancy and majority-vote decoding can suppress bit-flip errors in a minimal quantum error-correction setting. Using **Qiskit**, the protocol is simulated for a range of physical error probabilities and compared to the unprotected case.

---

## Repository Structure

```text
.
├── src/
│   └── QRepetitionCode.ipynb
├── report/
│   └── Report in PDF format
├── latex/
│   └── Supporting LaTeX material
└── README.md
```
---

## Methods

- **Framework:** Qiskit  
- **Error model:** Independent bit-flip errors with probability \( p \)  
- **Evaluation metric:** Logical error probability  
- **Simulation:** Repeated execution of the quantum circuit  

---

## Reproducibility

All simulations can be reproduced by running `QRepetitionCode.ipynb` from start to finish. The notebook contains the complete implementation and generates all figures used in the report.

---

## Requirements

- Python 3.9+
- Qiskit
- NumPy
- Matplotlib

---

## Source Code

The full source code is available at:  
https://github.dev/juliacher/Quantum-Error-Correction

