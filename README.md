# FANET Routing Optimization using SAO (MATLAB)

## Overview

This project simulates a Flying Ad-hoc Network (FANET) consisting of multiple UAVs communicating in a dynamic environment. The simulation compares conventional random peer selection with a Score-based Adaptive Optimization (SAO) routing algorithm.

The proposed SAO algorithm selects communication peers based on:

- Link Quality
- Residual Energy
- Distance Penalty
- Load Balancing

The simulation evaluates overall network performance using several communication metrics.

---

## Features

- Dynamic UAV mobility
- Random routing baseline
- SAO-based intelligent routing
- Energy-aware communication
- Load balancing
- Link stability analysis
- Network lifetime estimation
- Automatic CSV result generation
- Multiple performance graphs

---

## Simulation Parameters

| Parameter | Value |
|-----------|-------|
| Number of UAVs | 25 |
| Area Size | 300 × 300 |
| Communication Range | 250 |
| Initial Energy | 100 |
| Simulation Steps | 50 |
| Step Size | 10 |

---

## SAO Routing Metrics

The routing score is calculated using:

Score =
w1 × Link Quality +
w2 × Residual Energy +
w4 × Load Balance -
w3 × Distance Penalty

Weights:

- Link Quality = 0.4
- Energy = 0.3
- Distance = 0.2
- Load Balance = 0.6

---

## Performance Metrics

The simulation compares:

- Throughput
- Energy Consumption
- Delay
- Fairness Index
- Load Variance
- Network Lifetime
- Link Stability

---

## Output

The program generates:

- Dynamic FANET visualization
- Throughput comparison
- Energy comparison
- Delay comparison
- Fairness comparison
- Load distribution plots
- Load variance plot
- CSV file containing simulation results

---

## Requirements

MATLAB R2021a or later

No external toolboxes required.

---

## How to Run

1. Clone the repository

2. Open MATLAB

3. Open `fanet.m`

4. Run the script

The simulation automatically displays graphs and saves results into:

fanet_results.csv

---

## Project Structure

fanet.m

fanet_results.csv

README.md

LICENSE

.gitignore

---

## Future Improvements

- 3D UAV mobility
- Real wireless channel models
- Obstacle-aware routing
- Machine Learning based routing
- Reinforcement Learning optimization
- NS-3 implementation
- Integration with ROS/Gazebo

---

## Author

Sai Pradnesh
