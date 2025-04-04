# **Federated Quantum Generative Adversarial Network (FQGAN)**  

This repository contains a Python implementation of a **Federated Quantum Generative Adversarial Network (FQGAN)** using PyTorch and Qiskit. The project explores the integration of quantum circuits for the generator and classical neural networks for the discriminator, aimed at generating synthetic data that mimics real data distributions for Intrusion Detection, with a distributed approach.  

## **Project Overview**  

This implementation leverages quantum machine learning to train a federated hybrid **Quantum-Classical Generative Adversarial Network**.  
- The **generator** utilizes quantum circuits based on Qiskit's `SamplerQNN`, a parameterized quantum circuit architecture enhanced with feature maps and ansatzes.  
- The **discriminator** is a classical feedforward neural network built using PyTorch for binary classification.
Each single QGAN works on different data and after each epoch the generator and the discriminator weights are aggragated to improve robustness, scalability and privacy.  

The project demonstrates:  
1. **Quantum circuit design** for generative models.  
2. **Training adversarial networks** combining quantum and classical components.  
3. An **interpret function** that maps quantum outputs (measurements of qubit states) to input features resembling real data distributions. 
4. A **distribuited approach** for enhancing the efficiency of the model. 

## **Citation**  

If you plan to use this code for your work, please cite the associated paper once it is published. Kindly check back on this GitHub page for updates regarding the publication status and citation information.

## Acknowledgment
This research is funded by the NGIsargasso project (Europe Horizon Grant No. 101092887), Open Call 4  FRQGAN4AD project. 

## Contact
Anonymous
