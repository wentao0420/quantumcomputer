# quantumcomputer

Course: How does a quantum computer work? 

Submission by
Name, mail, matrix
Name, mail, matrix
Name, mail, matrix
Name, mail, matrix

on 19th December 2022

---

This Library that we found is a library for Python which made it possible to run quantum computing simulations on an ordinary computer (it was a kind of a virtual quantum computer).

The basic units of information in quantum computing which are implemented in the library are qubits and quantum registers. Qubit is a normalised vector in the two-dimensional, complex Hilbert state space of two-level quantum system. The coordinates of the vector define the probability of observing the qubit base states. Therefore, the qubit |Phi> holds the superposition of two basic states |0> and |1>, simultaneously:

|Phi> = alpha |0> + beta |1>

where |alpha|^2 + |beta|^2 =1 . The complex numbers alpha and beta are probability amplitudes, and the probability of observing the base states |0> and |1> are |alpha|^2 and |beta|^2, respectively. The vectors |0> and |1> form the canonical basis of the two-dimensional, complex space of possible qubit states. Using Dirac notation, the qubit state can be also rewritten as a column vector.

The basic classes of the model are QRegister, representing a quantum register, and an abstract class QuantumGate, representing any given quantum gate. Concrete classes inherit from QuantumGate and overwrite the definition of the compute method. 

This library uses overloaded operators to wrap operations on unitary matrices which allows to express any quantum circuits. The operator ** hides the tensor product operation, while the overloaded operator * hides the composition mapping function, which corresponds to serial gate connection in a quantum circuit. Moreover, the overloaded operator () makes it possible to “call” the gates or quantum circuits and execute them in a way similar to quantum functions.

We have used this library and tested it and it works.
