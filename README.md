# quantumcomputer

### Blockseminar: How does a quantum computer work? 

---

Submission on *19th December 2022*, by

+ **Ereny Magdy Ramzy Shehat (eshehat@uni-osnabrueck.de, 999995)**

+ **Boon Tao Chew (bchew@uni-osnabrueck.de, 1000156)**

+ **Eric Hrybinski (ehrybinski@uni-osnabrueck.de, 973564)**

+ **Paul Neuhaus (pneuhaus@uni-osnabrueck.de, 996906)**


---

### About the library (obtained from the Library Owner)

This library that we found is a Python library which made it possible to run quantum computing simulations on an ordinary computer.

The basic units of information in quantum computing which are implemented in qclib library are qubits and quantum registers. Qubit is a normalised vector in the two-dimensional, complex Hilbert state space of two-level quantum system. The coordinates of the vector define the probability of observing the qubit base states. Therefore, the qubit |Phi> holds the superposition of two basic states |0> and |1>, simultaneously:

|Phi> = alpha |0> + beta |1>

where |alpha|^2 + |beta|^2 =1 . The complex numbers alpha and beta are probability amplitudes, and the probability of observing the base states |0> and |1> are |alpha|^2 and |beta|^2, respectively. The vectors |0> and |1> form the canonical basis of the two-dimensional, complex space of possible qubit states. Using Dirac notation, the qubit state can be also rewritten as a column vector.

The basic classes of the model are QRegister, representing a quantum register, and an abstract class QuantumGate, representing any given quantum gate. Concrete classes inherit from QuantumGate and overwrite the definition of the compute method.

This qclib library uses overloaded operators to wrap operations on unitary matrices which allows to express any quantum circuits. The operator ** hides the tensor product operation, while the overloaded operator * hides the composition mapping function, which corresponds to serial gate connection in a quantum circuit. Moreover, the overloaded operator () makes it possible to “call” the gates or quantum circuits and execute them in a way similar to quantum functions.

### How do we find this library?

By Google search engine we found the LinkedIn account of a professor named "Dr. Robert Nowotnaik" who has implemented a quantam library by python in his master degree in 2008. He targeted educational and demonstrative purposes in tasks small and trivial in size.


### Why do we choose this library?

The library defines various quantum gates that can be important in building blocks for many quantum algorithms:

- Identity (It is often used as a placeholder in quantum circuits to maintain the proper number of qubits)
- Hadamard (It is often used to prepare qubits for quantum algorithms and is an important building block for many quantum algorithms)
- CNot
- Not
- Phaseshift
- Toffoli (Controlled Not gate)
- Fredkin (Controlled Swap gate)
- Swap
- Arbitrary (It is a quantum gate that can perform any operation on a quantum state that is allowed by the laws of quantum mechanics. It is often used the design and analysis of quantum algorithms and it is very useful for exploring the capabilities and limitations of quantum computers)
