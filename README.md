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

## Requirements

- **Python:** 3.9 or newer  
  (tested with Python 3.13)

- **Python libraries:**
  - qiskit
  - qiskit-aer
  - numpy
  - matplotlib
  - pylatexenc

---
## Running the code

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook src/QRepetitionCode.ipynb
   ```

2. Run all cells from top to bottom to:
   - construct the encoding and syndrome extraction circuits,
   - simulate single-qubit bit-flip errors,
   - verify syndrome measurements,
   - visualize the quantum circuits,
   - reproduce the reported results.

---
## Reproducibility

All simulations can be reproduced by running `QRepetitionCode.ipynb` from start to finish. The notebook contains the complete implementation and generates all figures used in the report.

---

## Source Code

The full source code is available at:  
https://github.dev/juliacher/Quantum-Error-Correction

