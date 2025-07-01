# Learning Time-Varying Quantum Lossy Channels

This repository contains the code accompanying the paper:

**Title:** _Learning Time-Varying Quantum Lossy Channels_  
**Authors:** Angela Rosy Morgillo*, Stefano Mancini, Massimiliano F. Sacchi and Chiara Macchiavello  
**Reference:** Angela Rosy Morgillo, Stefano Mancini, Massimiliano F. Sacchi, and Chiara Macchiavello <i>*"Learning Time-Varying Quantum Lossy Channels"*</i> (2025)
Reference: Simone Roncallo, Angela Rosy Morgillo, Chiara Macchiavello, Lorenzo Maccone and Seth Lloyd <i>“Quantum optical classifier with superexponential speedup”</i> (2024)


> Time-varying quantum channels are essential for modeling realistic quantum systems with evolving noise properties.  
> In this work, we study *Gaussian lossy channels* that vary from one use to another.  
> Neural networks are employed to **classify**, **regress**, and **forecast** these channels based on their Choi-Jamiolkowski states.

## 📁 Project Structure
- `tvc.py`: Contains the core functions used throughout the project and imported by the other scripts.
- `classification.ipynb`: Code for generating datasets and training neural networks to classify quantum channel types (e.g., memoryless, Markovian, non-Markovian, compound, deterministic).
- `regression.ipynb`: Code for training neural networks to regress the transmissivity parameter sequence from time series of covariance matrix components associated with lossy Gaussian channels.
- `forecasting.ipynb`: Code for training neural networks to forecast future values of the transmissivity parameter sequence from time series of covariance matrix components associated with lossy Gaussian channels.
  

[![arXiv](https://img.shields.io/badge/arXiv-2504.12810-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2504.12810)
