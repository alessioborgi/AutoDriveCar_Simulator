# AutoDriveCar Simulator: Autonomous Driving Car using CNNs

### Copyright © 2024 Alessio Borgi


This project involves using a deep learning model, potentially for autonomous driving or related tasks, within a simulation environment. It utilizes PyTorch and PyTorch Lightning for building, training, and evaluating neural network models.

<div style="text-align: center">
  <a href="https://www.youtube.com/watch?v=kTxvHfCZaSY">
    <p style="font-size: 16px; margin-top: 5px;">Click the Photo to See the Video!</p>
    <img src="img/video_img.png" alt="Screenshot" width="1200"/>
  </a>
</div>


## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The AutoDrive Car Simulator provides a virtual environment for developing and testing autonomous driving algorithms. This repository contains scripts for building and training machine learning models to process simulated data, helping researchers and developers test their models in realistic driving scenarios.

## Features

- Deep learning model training using PyTorch and PyTorch Lightning.
- Support for various image processing techniques and datasets.
- Modular and customizable neural network architecture.
- Evaluation metrics include accuracy, F1 score, precision, and recall.

## Installation

Clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/alessioborgi/AutoDriveCar_Simulator.git
cd AutoDriveCar_Simulator
pip install -r requirements.txt```

## Usage

To start the simulation and model training:

1. Open the main simulation or training script (either a `.py` or `.ipynb` file).
2. Adjust parameters in the configuration file (e.g., `config.yaml`) as needed.
3. Run the script using the following command:

```bash
python simulator.py```

## Model Training and Evaluation

- **Training**: The project includes deep learning model training using libraries like PyTorch and PyTorch Lightning. To start training, modify the dataset path and hyperparameters in the provided notebook or script. After configuring, run the notebook cells or execute the script to begin training the model.

- **Evaluation**: The project provides various metrics to evaluate the model's performance, including accuracy, F1 score, precision, and recall. Ensure you specify the correct dataset and model checkpoint paths in the evaluation script or notebook before running the evaluation process.

### Example Commands

To train a model, use the command:

```bash
python train_model.py --config config.yaml```

To evaluate a model with a specific checkpoint, use:

