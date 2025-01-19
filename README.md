# Quantum HHL Simulation Project

This repository contains the documentation, and analysis for implementing the Harrow-Hassidim-Lloyd (HHL) algorithm to solve linear systems using quantum computing principles. The project focuses on solving a specific 2-dimensional non-Hermitian linear system, converted into a Hermitian form, and simulating the solution using the PennyLane framework.

## **Project Overview**
The HHL algorithm is a cornerstone of quantum computation, enabling efficient solutions to linear systems of equations in \( O(\log N) \) compared to \( O(N) \) in classical computation for sparse matrices. This project builds upon prior research by:
- Transforming non-Hermitian systems into Hermitian systems.
- Implementing quantum circuits with three registers: ancilla, eigenvalue encoding, and solution registers.
- Modifying and simulating the algorithm using PennyLane.
- Comparing theoretical and simulated results.

## **Key Files**
1. **Presentation Slides.pdf**
   - Provides an overview of the theoretical underpinnings, challenges, and potential of quantum algorithms for linear systems.
   - Discusses eigenvalues, eigenvectors, and implementation details for the HHL algorithm.

2. **HHL_Project_Report.pdf**
   - Detailed description of the ECS417 course project under Dr. Ankur Raina, IISER Bhopal.
   - Includes the mathematical formulation, quantum circuit design, and simulation results using PennyLane.
   - Highlights modifications to the original HHL algorithm for a specific non-Hermitian 2D system.

## **Key Results**
- **Efficiency:** Demonstrated \( O(\log N) \) complexity for sparse matrices.
- **Simulation Outcome:** Normalized solution set [1, 0], deviating slightly from the expected normalized solution [0.707, 0.707].
- **Challenges:** Approximation errors during controlled rotation operations and the need for pre-computed oracles.

## **Technologies Used**
- **Quantum Computing Framework:** PennyLane
- **Mathematics Software:** Mathematica (for oracle calculation)
- **Quantum Circuits:** Designed using quantum gates, ancilla qubits, and controlled rotations.

## **References**
- [HHL Analysis and Simulation Verification Based on Origin Quantum Platform](https://doi.org/10.1088/1742-6596/2113/1/012083) by Liu et al.
- [Using Quantum Algorithms to Solve Linear Systems](https://dl.uncw.edu/etd/2019-1/byrdm/michaelbyrd.pdf) by Michael C.R. Byrd Jr.

## **Acknowledgments**
- **Instructor:** Dr. Ankur Raina, IISER Bhopal
- **Contributors:** A. A. Gandhi, Rehan

## **Future Scope**
- Refining approximations to improve solution accuracy.
- Extending the algorithm to larger systems and exploring error mitigation techniques.
- Exploring applications of HHL in real-world quantum computing tasks.

---

This repository is a demonstration of the power and limitations of quantum algorithms and a step toward harnessing quantum computing for practical problem-solving.
