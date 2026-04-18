# IBM Quantum Learning - Self-Study Repository

[![Qiskit](https://img.shields.io/badge/Qiskit-2.3.0-blue.svg)](https://qiskit.org)
[![Python](https://img.shields.io/badge/Python-3.11.9-blue.svg)](https://www.python.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 1. Description

This repository documents my personal self-study journey through the **IBM Quantum Learning** courses (available at [learning.quantum.ibm.com](https://learning.quantum.ibm.com)).

The goal is **deep conceptual understanding**. For every module that includes Qiskit implementations (which is nearly all of them), I have written my **own code from scratch** — no copy-pasting of the official solutions. Each implementation is accompanied by detailed explanations, mathematical derivations, and personal notes on why certain design choices were made.

This repo serves as:

- A living portfolio of my quantum computing and quantum machine learning progress
- A reference for future projects and interviews
- A transparent record of my learning path for academic or professional purposes

**Note:** All code runs on Qiskit simulators by default. IBM Quantum hardware access (via free IBM Quantum account) is optional but fully supported.

## 2. Content

The repository is organized exactly following the official IBM Quantum Learning course structure. Each course has its own top-level folder containing Jupyter notebooks (`.ipynb`) for every module, plus any supporting Python scripts.

### Understanding Quantum Information & Computation

#### Basics of Quantum Information

- Single Systems
- Multiple Systems
- Quantum Circuits
- Projections and Projective Measurements
- Limitations on Quantum Information
- Quantum Entanglement

#### Fundamentals of Quantum Algorithms

- Quantum query algorithms
- Quantum algorithmic foundations
- Phase estimation and factoring
- Grover’s algorithm

#### General Formulation of Quantum Information

- Density matrices
- Quantum channels
- General measurements
- Purifications and fidelity

#### Foundations of Quantum Error Correction

- Correcting quantum errors
- The stabilizer formalism
- Quantum code constructions
- Fault-tolerant quantum computing

### Quantum Machine Learning (QML)

#### Quantum Machine Learning

- Introduction
- Classical machine learning review
- Data encoding
- Quantum Kernels
- QVCs and QNNs

#### Variational Algorithm Design

- Variational algorithms
- Reference states
- Ansaetze and variational forms
- Cost functions
- Optimization loops
- Instances and extensions
- Examples and applications

### Folder Structure Example (inside each course folder):

> ```
> Basics_of_Quantum_Information/
> ├── 1-single-systems.ipynb
> ├── 2-multiple-systems.ipynb
> ├── 3-quantum-circuits.ipynb
> ├── 4-projections-and-projective-measurements.ipynb
> ├── 5-quantum-information-limitations.ipynb
> ├── 6-quantum-entanglement.ipynb
> ```

## 3. Project Setup and Installation

### Prerequisites

- Python 3.10 or higher
- Git
- (Optional but recommended) IBM Quantum account for hardware execution

### Step-by-step Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/Mir-Ilham/qiskit-ibm-quantum-study
   cd qiskit-ibm-quantum-study
   ```

2. **Create and activate a virtual environment** (recommended)

   ```bash
     python -m venv venv
     .venv\Scripts\activate
   ```

3. **Install all required packages with exact versions**

   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

   or

   ```bash
   python -m notebook
   ```

## 4. How to Use This Repository

- Navigate to the course folder of your interest.
- Open the corresponding .ipynb file.
- Run cells sequentially — every notebook contains:
  - Theory recap (Concise)
  - Mathematical background
  - Qiskit implementations
  - Experiments / parameter sweeps
  - Personal observations and "gotchas"

Feel free to explore, fork, or use any part of the code in your own projects (MIT license).

## 5. Acknowledgments

IBM Quantum Learning team and Prof. John Watrous for creating these outstanding free courses.
Qiskit development community for the excellent open-source framework.
