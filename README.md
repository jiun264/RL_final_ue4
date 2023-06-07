# Repository Name

## Introduction

This repository provides instructions and code for working with the **hitgub** project. The project utilizes a **3070ti** GPU and **CUDNN 8.6** for accelerated performance. This document outlines the steps to set up the necessary dependencies and get started with the project.

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

