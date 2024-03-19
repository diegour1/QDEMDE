# Quantum density estimation with density matrices: Application to quantum anomaly detection

![](https://raw.githubusercontent.com/diegour1/QDEMDE/main/Images/QDEMDE_Method3.jpg)

Implementation of the article:

- Diego H. Useche, Oscar A. Bustos-Brinez, Joseph A. Gallego-Mejia, and Fabio A.
Gonz ́alez. Quantum density estimation with density matrices: Application
to quantum anomaly detection. Phys. Rev. A, 109:032418, Mar 2024.
doi: 10.1103/PhysRevA.109.032418. URL [https://link.aps.org/doi/10.1103/PhysRevA.109.032418](https://link.aps.org/doi/10.1103/PhysRevA.109.032418).

## Abstract

Density estimation is a central task in statistics and machine learning. This problem aims to determine the underlying probability density function that best aligns with an observed dataset. Some of its applications include statistical inference, unsupervised learning, and anomaly detection. Despite its relevance, few works have explored the application of quantum computing to density estimation. In this article, we present a quantum-classical density-matrix density estimation model, called Q-DEMDE, based on the expected values of density matrices and a quantum embedding called quantum Fourier features. The method uses quantum hardware to build probability distributions of training data via mixed quantum states. As a core subroutine, we propose an algorithm to estimate the expected value of a mixed density matrix from its spectral decomposition on a quantum computer. In addition, we present an application of the method for quantum-classical anomaly detection. We evaluated the density estimation model with quantum random and quantum adaptive Fourier features on different datasets on a quantum simulator and a real quantum computer. An important result of this work is to show that it is possible to perform density estimation and anomaly detection with high performance on present-day quantum computers.

## Density estimation datasets

The two-dimensional density estimation datasets can be downloaded from the following link: 

- https://zenodo.org/records/7822851

## Anomaly detection dataset

The modified Cardiotography data set can be downloaded from the following link:

- http://odds.cs.stonybrook.edu/cardiotocogrpahy-dataset/
