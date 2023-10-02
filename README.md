# **POVM measurement based quantum teleportation protocol**
## **Summer Internship, IISER, Kolkata** 

**Supervisor:** [Prasanta K. Panigrahi](https://scholar.google.co.in/citations?user=sNq6fwwAAAAJ&hl=en)

The project [report]() in the folder `Report'.

## **Project Description:**

In quantum mechanics poaitive operator-valued measures (POVM) describribe the most general form of quantum measurement. A deterministic method to perform a general POVM can be implemented using Neumark's dilation theorem, which states that a POVM of n elements can be performed as a projective measurement in an n dimensional spaace. We described a general single qubit POVM on a circuit based quantum computer using Neumark's theorem. When we perform quantum teleportation form one party to multiple parties, there are always possibility to lose information. We provide a POVM measurement based protocol to maximize the information gain, expected average of the values of the recieved information (this includes the possibility that some type of information never recieved). Even a measurement fails to identify with certainty a information, it is still usally possible to artibute to the observer aquaires at least some mutual information. We discuss the extansion of this work to space with more than three dimension. 

## **Key Results:**
1) We describe PVM & POVM measurement and the relation betweeen them using Neumark's dilation theorem.
2) We simulated a general single qubit two and three elements POVM on a circuit based quantum computer.
3) We implemented POVM measurement on quantum information splitting and calculated the fidelity.
4) We generalized this in POVM measurement based quantum teleportation portocol.
5) We also address the questions how to maximize the information gain, expected average of the values of the recieved information (this includes the possibility that some type of information never recieved). Even a measurement fails to identify with certainty a information, it is still usally possible to artibute to the observer aquaires at least some mutual information.
7) We discuss the extansion of this work to space with more than three dimension.

## **Code Repo Descriptions:**
1) Folder Simulation of POVM has code for simulation two and three element POVM. These codes are used in the analysis presented in Sec. (III) of the report.
2) Folder QIS using 5-qubit cluster state has code for the Quantum information splitting circuits using 5-qubit cluster state that we have presented in Sec. (IV) of the report. These codes contain genaration of cluster state and fidelity calculation without using POVM. These codes are used to generate the plots shown in Fig. (3) and Fig. (4) of the report.
3) Folder Implementation of POVM on QIS has code for the analysis of POVM on Quantum information splitting presented in Sec. (II) of the report. There is also a code for generating a data set shown in Fig. (1) of the report. 

## **References:**

[1] Yordan S. Yordanov and Crispin H. W. Barnes, “Implementation of a general single-qubit positive operator-valued measure on a circuit-based quantum computer” Phys. Rev. A 100, 062317 (2019); Erratum Phys. Rev. A 107, 049901 (2023)
