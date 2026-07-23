# Quantum-Computing
Series of Quantum Algorithms in IBM Qiskit as part of a final project for Quantum Computing at Dakota State University. These algorithms serve as a continuation and implementation of prior work where we created proofs of each algorithm.

## Variation Quantum Eigensolver
The VQE finds the minimum eigenvalue of a Hamiltonian, otherwise known as the ground state of a physical system. This algorithm is used in quantum chemistry, simulations and optimization problems. Given an ansatz (fancy word for guess), the process calculates the expectation value of the observable and then optimizes the value using a classical system to improve the guess.   

<img width="382" height="128" alt="image" src="https://github.com/user-attachments/assets/31f4f568-3875-4e61-b982-159c68d19e65" />

## Quantum Adder
The Quantum adder is a basic arithmetic algorithm for adding quantum bits. Similar to its classical counterpart, the algorithm requires enough bits to account for each variable, as well as the carry bit, sum and for the quantum algorithm, a classical register to hold the result. Notably, this algorithm can only perform single qbit addition. Longer operations will require additional qbits and sequences of the algorithm for each additional bit.

### Quantum Adder running on Aer Simulator locally with diagram of circuit.
Below is the circuit representation of of the quantum adder and the result of running it on the Aer quantum simulater.

<img width="936" height="442" alt="image" src="https://github.com/user-attachments/assets/325147da-6b0e-4cbf-b972-e8f88b6acdf6" />

### Quantum Adder running on IBM Quantum Platform backend.
Below is the same Quantum Adder algorithm but is sent to the IBM Quantum backend to run on one of their quantum machines. 

<img width="462" height="52" alt="image" src="https://github.com/user-attachments/assets/1a601ac4-ac89-4610-a84d-6b9d49384f36" />
