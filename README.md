# Quantum Teleportation

This repository contains a Google Colab notebook that demonstrates **Quantum Teleportation** — one of the most fascinating protocols in quantum computing.  
Quantum teleportation allows the transfer of an unknown quantum state from one qubit to another **without physically sending the qubit itself**, using **entanglement**, **Bell-state measurements**, and **classical communication**.

---

## 📌 What’s Inside
- A detailed step-by-step explanation of the quantum teleportation protocol  
- Implementation using **Qiskit** in Google Colab  
- Visualization of circuits  
- Simulation results showing how the quantum state is successfully teleported  
- Code comments that explain each step in simple terms  

---

## 🔬 What is Quantum Teleportation?

Quantum teleportation is a process where:
1. Two qubits are entangled.
2. One qubit stays with *Alice* and the other with *Bob*.
3. Alice performs a Bell measurement on her qubits.
4. She sends Bob two classical bits.
5. Bob applies quantum gates depending on the classical bits.  
   
After this process, Bob's qubit becomes an exact copy of the original state Alice wanted to send — **even though the two never physically exchanged qubits**.

This protocol is essential in:
- Quantum communication  
- Quantum networking  
- Quantum cryptography  
- Building future quantum internet

---

## 📘 Notebook

You can open the Colab notebook here:

**[Quantum Teleportation Notebook (Google Colab)](https://colab.research.google.com/drive/1sodwpJFM0nZEimLRv7xOvM-raHEsoWUl?usp=sharing)**

Or explore the notebook in this repository.
