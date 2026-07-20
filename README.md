# Quantum-Computing
Series of Quantum Algorithms in IBM Qiskit as part of a final project for Quantum Computing at Dakota State University.

## Variation Quantum Eigensolver
The VQE finds the minumun eigenvalue of a Hamiltonian, otherwise know as the ground state of a physical system. This algortithm is used in quantum chemistry, simualtions and optimization problems. Given a ansatz (fancy word for guess), the process calculates the expectation value of the observable, and then optimizies the value using a classical system to improve the guess.   
<img width="382" height="128" alt="image" src="https://github.com/user-attachments/assets31f4f568-3875-4e61-b982-159c68d19e65" />


## Quantum Adder
The Quantum adder is a a basic arithmatic algorithm for adding quantum bits. Similar to it classical counterpart, the algorithm requires enough bits to account for each variable, as well as the carry bit, sum and for the quantum algorithm, a classical register to hold the result. Notably, this algorithm can only perfrom single qbit addition. Longer operations will require additional qbits and sequences of the algorithm for each additiional bit.

###  Quantum Adder running on Aer Simulator locally with diagram of circuit.
<img width="936" height="442" alt="image" src="https://github.com/user-attachments/assets/325147da-6b0e-4cbf-b972-e8f88b6acdf6" />


### Quantum Adder running on IBM Quantum Platform backend.

<img width="462" height="52" alt="image" src="https://github.com/user-attachments/assets/1a601ac4-ac89-4610-a84d-6b9d49384f36" />
