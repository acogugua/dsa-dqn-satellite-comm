# dsa-dqn-satellite-comm
Real‑time Dynamic Spectrum Allocation (DSA) for satellite communication using Deep Q‑Networks (DQN). The agent learns from the environment to allocate spectrum to ground users under GEO–LEO coexistence, improving spectral efficiency and reducing SLA violations. Includes demo, MATLAB scripts, and performance plots.

## Demo Videos

### Starlink Tracking Use Case
Tracking Starlink connection across multiple ground stations to measure access duration, RSSI, and SINR at different elevation angles for optimizing spectral efficiency in co-existing satellites.  
 [Watch the video on LinkedIn](https://www.linkedin.com/posts/clement-ogugua-asogwa-ph-d-70961b201_tracking-starlink-connection-for-a-use-case-activity-7330442286826160128-myM9/)

###  Dynamic Spectrum Allocation (DSA) with DQN
Real-time DSA demo showing how the agent learns to allocate spectrum to ground users under GEO–LEO coexistence.  
🎥 [Watch the DSA demo on LinkedIn](<insert your DSA demo link here>)



#  Dynamic Spectrum Allocation (DSA) with DQN in MATLAB

## Overview
This project demonstrates **real-time dynamic spectrum allocation (DSA)** for satellite communication using **Deep Q-Networks (DQN)** in MATLAB.  
The agent learns to allocate spectrum resources to ground users under GEO–LEO coexistence, improving spectral efficiency while respecting SLA constraints.

## Motivation
Satellite communication faces interference and bandwidth challenges. Reinforcement learning (RL) enables adaptive spectrum allocation, outperforming static methods.

## Approach
- **Environment:** Multi-user GEO–LEO downlink modeled in MATLAB.
- **Agent:** DQN implemented with MATLAB neural network toolbox.
- **Reward Function:** Balances throughput, fairness, and SLA compliance.
- **Scripts:** `train.m` (training loop), `evaluate.m` (performance metrics).

## Demo
 Watch the demo on [LinkedIn](www.linkedin.com/in/clement-ogugua-asogwa-ph-d-70961b201)

## Results
- Increased **spectral efficiency** compared to baseline allocation.
- Reduced SLA violations under dynamic load.
- Plots available in `/plots`.

## How to Run
1. Open MATLAB R2023a (or later).
2. Run `train.m` to train the agent.
3. Run `evaluate.m` to generate performance plots.

## Future Work
- Extend to multi-agent RL.
- Integrate with real satellite communication systems.
- Explore deployment on cloud-based simulation platforms.

## Connect
- [LinkedIn](www.linkedin.com/in/clement-ogugua-asogwa-ph-d-70961b201)
- [Email](mailto:clement.asogwa@deakin.edu.au or acogugua@yahoo.com)
