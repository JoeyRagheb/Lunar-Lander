


# Reinforcement Learning Final Assignment

### Project Team
**University of Bath, Department of Computer Science**
 - Eduardo Perez Denadai (epd29@bath.ac.uk)
 - Angela Kunanbaeva (ak3072@bath.ac.uk)
 - Connor Hoehn (ch2432@bath.ac.uk)
 - Joey Ragheb (jr2238@bath.ac.uk)
 - Edward Siew (ahs63@bath.ac.uk)

### Summary of Contents

| Title            | Description                                                                                                                                                 | Folder Path  |
|------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| DQN Agent        | A notebook containing the implementation and training of a DQN agent. Exported model parameters and related data.                                           | ./dqn        |
| DDQN Agent       | A notebook containing the implementation and training of a Double-DQN agent. Exported model parameters and related data.                                    | ./double-dqn |
| DDDQN Agent      | A notebook containing the implementation and training of a Double-Dueling-DQN agent. Exported model parameters and related data.                            | ./dddqn      |
| DDQN+PER Agent   | A notebook containing the implementation and training of a Double-DQN agent with Prioritized Experience Replay. Exported model parameters and related data. | ./ddqn-per   |
| DDPG Agent       | A notebook containing the implementation and training of a Deep Deterministic Policy Gradient agent. Exported model parameters and related data.            | ./ddpg       |
| Agent Comparison | A single notebook that examines the training rewards of each agent. Matplotlib charts are used to compare the training results of each agent.               | root         |
| Dependencies     | Conda environment configuration for training the agents using GPU or CPU compute devices.                                                                   | root         |
| Report           | The Latex files required to generate the Project report.                                                                                                    | ./report     |

### Overview

This repository contains all source code used for RL Assignment 2. We started off with the DQN model and then adapted for optimization. Therefore, you will see DDQN, DDDQ, and DDQN + PER. We also deviated from the DQN family with the DDPG agent.

We chose to use LunarLander simulation environment for consistency.

### Comparison Report

While all the agents live in their own independent subfolder, the performance of each agent is detailed in the compare notebook. This notebook plots the training performance of both each agent over 1000 episodes.

### Notes

The following section overviews pertinent for running the independent agent notebooks.

####  Environment Setup
To activate the environment from file use:

> $ cd my_folder/

> $ conda env create [--name <env_name>] --file=environment_gpu.yml

* [--name <env_name>] is optional if you wish to change default name in the config yaml

Our CUDA version was 10.1 so to replicate my tensorflow env with gpu use (changes to tf version may have to be changed):

* environment_gpu.yml

and for cpu environment:

* environment_cpu.yml


### Contact

Please feel free to contact us for assistance in running the notebooks.