# Advanced-AI-course

This repository contains the implementation and comparison of the **FORK** algorithm as presented in the paper:

**Title: [FORK: A Forward-Looking Actor for Model-Free Reinforcement Learning](https://arxiv.org/pdf/2010.01652)**

## Overview

This project reproduces the experiments from the original FORK paper and compares the results with our own findings.

### Implemented Algorithms
- **TDS_FORK**: FORK algorithm implemented using the TD3 framework.
- **SAC_FORK**: FORK algorithm implemented using the SAC framework.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.8+
- PyTorch
- Gym
- Jupyter Notebook
## Running the Code
### TDS_FORK (TD3)
To reproduce the results for the TDS_FORK algorithm, run the Jupyter notebook:
TD3_FORK_BipedalWalkerHardcore_Colab.ipynb. This notebook is designed to run in a Google Colab environment and should yield results consistent with those reported in the original paper.

### SAC_FORK
To run the SAC_FORK algorithm, execute the script:
python main_sac_fork.py. This script trains the model using the SAC framework with FORK enhancements.
