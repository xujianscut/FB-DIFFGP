

# Fully Bayesian Differential Gaussian Processes through Stochastic Differential Equations

This repository contains the code for the paper "Fully Bayesian Differential Gaussian Processes through Stochastic Differential Equations." The paper is currently under review at the *KBS Journal*.

## Overview

In this work, we propose a novel method for **Fully Bayesian Differential Gaussian Processes (FB-DiffGP)**, leveraging **Stochastic Differential Equations (SDEs)** for inference. The method aims to improve the expressiveness and efficiency of Gaussian Processes (GPs) by modeling them as differential equations, and we adopt a fully Bayesian approach to parameter estimation.

## Features

- **Bayesian Inference**: The framework uses a fully Bayesian approach for parameter estimation, incorporating uncertainty quantification.
- **Differential Equations**: The model leverages SDEs to define the dynamics of the GP, enhancing flexibility and scalability.


## Requirements

To run the code, ensure that you have the following dependencies installed:

- Python 3.x
- PyTorch
- NumPy
- SciPy
- Matplotlib
- Other libraries specified in `requirements.txt`


## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/xujianscut/FB-DiffGP.git
    cd FB-DiffGP
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the code:

    Replace `<dataset_name>` with the name of the dataset you wish to use (e.g., `UCI`).


## Citation

If you use this code in your research, please cite the following paper:

```bibtex
@article{xu2024fully,
  title={Fully Bayesian Differential Gaussian Processes through Stochastic Differential Equations},
  author={Xu, Jian and Lin, Zhiqi and Chen, Min and Yang, Junmei and Zeng, Delu and Paisley, John},
  journal={arXiv preprint arXiv:2408.06069},
  year={2024}
}

```
