Quantum Measurement Error Mitigation Lab

This project demonstrates measurement (readout) error mitigation in quantum circuits using Qiskit Aer. It models realistic readout noise via a confusion matrix and applies classical post-processing to recover mitigated measurement probabilities, a critical technique for NISQ-era quantum computing.

Features

Readout noise modeling using confusion matrices

Measurement error mitigation via matrix inversion

Interactive UI using ipywidgets

Visualization of noisy vs mitigated probabilities

Fully compatible with Google Colab

Concepts Covered

Quantum measurement errors

Noise models in Qiskit Aer

Classical error mitigation techniques

NISQ hardware limitations

Requirements

Python 3.9+

Qiskit

Qiskit Aer

NumPy

Matplotlib

ipywidgets

How to Run

Open the notebook in Google Colab

Install dependencies (included in the notebook)

Select input state and readout noise probability

Run the experiment to compare noisy vs mitigated results

Output

Bar plot comparing noisy and mitigated measurement probabilities

Clear visualization of mitigation effectiveness

Applications

Quantum hardware benchmarking

Error mitigation research

Teaching quantum noise concepts

Pre-processing for variational algorithms

Keywords

Quantum Computing, Measurement Error Mitigation, Qiskit, NISQ, Noise Modeling, Readout Error
