# Smart-Traffic-Simulation-using-LSTM-and-DQN
## System Overview

![Smart Traffic Management System Architecture](assets/images/system_architecture.png)

*Figure 1: Overall architecture of the proposed smart traffic management system integrating LSTM-based traffic prediction with DQN-based adaptive signal control.*

This repository contains the implementation of a traffic congestion modeling and simulation system based on artificial intelligence techniques.

## System Workflow

The proposed system follows the workflow illustrated in Figure 1. 
Traffic data are first processed and used to train an LSTM model for short-term traffic prediction.
The predicted traffic flow, together with the current traffic state, is then provided as input to a Deep Q-Network (DQN) agent.
Based on this combined state representation, the DQN agent dynamically optimizes traffic signal timings within the simulation environment to reduce congestion and improve overall traffic flow.
This figure represents the overall architecture of my proposed system.
Traffic data are first analyzed using an LSTM model to predict future traffic demand.
These predictions are combined with the current traffic state and passed to a DQN agent, which learns an optimal signal control policy through interaction with the simulated environment.
The main advantage of this architecture is that it allows the system to move from reactive traffic control to predictive and adaptive decision-making.

سا
