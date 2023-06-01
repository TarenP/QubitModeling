# QubitModeling

# Quantum Qubit Sampling and 3D Modeling

This repository contains code snippets related to quantum qubit sampling and generating a 3D model based on the sampled measurements. The code utilizes quantum computing simulations and geometric operations on 3D meshes. Let's take a look at each code segment:

## 1. Quantum Qubit Sampling

The code segment `qiskit_qubit_sampling.py` demonstrates the process of sampling measurements from a quantum qubit using the Qiskit library. It imports necessary libraries, sets up a quantum circuit with a variable number of qubits, applies quantum gates, measures the qubits, and records the measurement results. The measurement results are then stored in a CSV file for further analysis.

## 2. 3D Modeling Based on Qubit Sampling

The code segment `pyvista_qubit_modeling.py` utilizes the PyVista library to generate a 3D model based on the sampled qubit measurements. It imports the necessary libraries, defines functions to process the measurement data, and creates a 3D mesh (a sphere) using PyVista. The code then iterates over the measurement data, calculates coordinates based on the measurements, and modifies the mesh accordingly. Finally, it visualizes the resulting 3D model and saves it as an STL file.

## Usage

1. Clone the repository:


2. Quantum Qubit Sampling:
   - Install the required libraries:
     ```
     pip install qiskit pandas
     ```
   - Run the code:
     ```
     python qiskit_qubit_sampling.py
     ```

3. 3D Modeling Based on Qubit Sampling:
   - Install the required libraries:
     ```
     pip install pyvista numpy
     ```
   - Run the code:
     ```
     python pyvista_qubit_modeling.py
     ```

Feel free to explore and modify the code snippets based on your requirements, but make sure to give credit! The `qiskit_qubit_sampling.py` code gathers qubit measurement data, and `pyvista_qubit_modeling.py` generates a 3D model based on the sampled measurements.

