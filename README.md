#  Quantum Treasure Hunt  
**Grover’s Search Lite + Quantum State Tomography**

This project uses a simplified version of **Grover’s algorithm** to find a hidden "treasure" (a marked quantum state) in a 3-qubit system using **Qiskit**.

---

##  What It Does

- Marks a secret state (e.g., `|101⟩`) using an oracle.
- Amplifies its probability using amplitude amplification (Grover Lite).
- Measures the circuit and checks if the hidden state is found.
- Bonus: Rebuilds the oracle with basic gates and visualizes states.

---

Key Features
-3-qubit quantum circuit
-Oracle with phase flip
-Grover-style diffusion
-Measurement with 100 shots
-Histogram & Bloch vector visualizations

