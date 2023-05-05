Final project for CPSC 452/552 Spring 2023.

### Team members:
Jakub Bester, Nikhil Harle, Frank Li, Ioannis Panitsas, Connor Totilas

## Introduction
DO THIS

## Code Summary
You can train any of the QCNN models/variations in the `qcnn_training.ipynb` notebook, where the training process is nicely explained.
The source code is in the `source` folder, and consists of four files:
1. `models.py`
Contains all of the QCNN architectures, the classical benchmarking, and variations on the base architecture.
2. `state_prep.py`
Contains code to generate Majorana modes.
3. `train_funcs.py`
Contains training and testing implementations/logic.
4. `utils.py`
Contains various utility functions.

## TODOs:
1. Write paper (**everybody!!**)
  
2. Try for different (topological) state - **Connor**
  - Find Qiskit circuit that prepares the state and add code to Github in the form of a function like QCNN.prepare_majorana()
  - Ideas: AKLT, cluster state with excitation, whatever we want!

3. Rewrite models.py 
  - make it so that we're not initializing all trainable gates separately
  - generalize to *n* qubits instead of just 8

4. Make a phase diagram of the best architecture
