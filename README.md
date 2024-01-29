# RL_final_ue4
![image](https://github.com/jiun264/RL_final_ue4/assets/121162358/2a19fa1e-a90b-4b59-bf0b-2521bae62742)

## Features
- Utilizes the UnrealCV library for communication with Unreal Engine.
- Implements a Deep Q-Network (DQN) agent for reinforcement learning.
- Uses convolutional neural networks (CNNs) for visual perception.
- Supports continuous state and action spaces.
- Provides a customizable environment for training and evaluation.

## Introduction
Training an ai agent with dqn to find a door in realisticroom enviroment
This repository provides instructions and code for working with the **gitgub** project. The project utilizes a **3070ti** GPU and **CUDNN 8.6** for accelerated performance. This document outlines the steps to set up the necessary dependencies and get started with the project.

## Installation

To begin, follow the steps below to set up the project environment:

1. Create a new conda environment:
    ```shell
    conda create --name new_environment_name python=3.10
    ```

2. Activate the newly created environment:
    ```shell
    conda activate new_environment_name
    ```

3. Install TensorFlow 2.10:
    ```shell
    conda install tensorflow=2.10
    ```

4. Install the TensorFlow DirectML plugin:
    ```shell
    pip install tensorflow-directml-plugin
    ```

https://github.com/jiun264/RL_final_ue4/assets/121162358/e1e40ea1-0ffc-448d-9386-568624755318



5. Install Matplotlib from conda-forge:
    ```shell
    conda install -c conda-forge matplotlib
    ```

6. Install UnrealCV:
    ```shell
    pip install unrealcv
    ```

7. Install CUDA Toolkit 11.8:
    ```shell
    conda install cudatoolkit=11.8
    ```

8. Install OpenCV from conda-forge:
    ```shell
    conda install -c conda-forge opencv
    ```

9. Install NumPy:
    ```shell
    conda install numpy
    ```

## Usage

Once the installation is complete, you can proceed with running the project. Make sure to activate the conda environment before executing any code.

```shell
conda activate new_environment_name

