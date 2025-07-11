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

##  Key Features

-  **3-qubit quantum circuit**  
  A simple and efficient quantum system setup for experimentation.

-  **Oracle with phase flip**  
  Marks the hidden state using a Z-gate or custom gate logic.

-  **Grover-style diffusion**  
  Amplifies the probability of measuring the marked state.

-  **Measurement with 100 shots**  
  Collects meaningful statistical data to confirm the result.

-  **Histogram & Bloch vector visualizations**  
  Visual feedback to observe the probability distribution and quantum state evolution.

