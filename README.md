# Quantum-Computing-Steganography

## Quantum Message Hiding
This Python script demonstrates the concept of hiding a binary message within a quantum circuit using superposition and entanglement.

## Overview
The script allows users to:

Enter a binary message they want to hide.
Specify the length of the quantum carrier circuit.
Encode the message into the carrier circuit by applying quantum gates.
Simulate the carrier circuit to obtain measurement outcomes.
Extract the hidden message from the measurement outcomes.

## How It Works
Message Encoding: The input binary message is encoded into a quantum circuit by applying Hadamard gates for superposition and CNOT gates for entanglement.
Simulation: The encoded quantum circuit is simulated using the Qiskit Aer simulator to obtain measurement outcomes.
Message Extraction: The most probable outcome is selected, representing the hidden message.

## Usage
Clone the repository.
Install the required dependencies (qiskit, qiskit-aer).
Run the script.
Follow the prompts to input the message and carrier length.

## Dependencies
Qiskit
Qiskit Aer
