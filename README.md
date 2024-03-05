# Quantum density estimation with density matrices: Application to quantum anomaly detection

![](https://raw.githubusercontent.com/diegour1/QDEMDE/main/Images/QDEMDE_Method3.jpg)

Implementation of the Q-DEMDE method: Quantum-classical density matrix density estimation

- Diego H Useche, Oscar A Bustos-Brinez, Joseph A Gallego, and Fabio A González. Quantum density estimation with density matrices: Application to quantum anomaly detection. arXiv preprint arXiv:2201.10006, 2022.

## Abstract

Density estimation is a central task in statistics and machine learning. This problem aims to determine the underlying probability density function that best aligns with an observed data set. Some of its applications include statistical inference, unsupervised learning, and anomaly detection. Despite its relevance, few works have explored the application of quantum computing to density estimation. In this article, we present a novel quantum-classical density matrix density estimation model, called Q-DEMDE, based on the expected values of density matrices and a novel quantum embedding called quantum Fourier features. The method uses quantum hardware to build probability distributions of training data via mixed quantum states. As a core subroutine, we propose a new algorithm to estimate the expected value of a mixed density matrix from its spectral decomposition on a quantum computer. In addition, we present an application of the method for quantum-classical anomaly detection. We evaluated the density estimation model with quantum random and quantum adaptive Fourier features on different data sets on a quantum simulator and a real quantum computer. An important result of this work is to show that it is possible to perform density estimation and anomaly detection with high performance on present-day quantum computers.

## Density estimation dataset

The two-dimensional density estimation datasets can be downloaded the following link: 

- https://zenodo.org/records/7822851

## Anomaly detection dataset

The modified Cardiotography data set can be downloaded from the following link:

- http://odds.cs.stonybrook.edu/cardiotocogrpahy-dataset/
