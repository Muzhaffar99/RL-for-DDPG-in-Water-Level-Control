# RL for DDPG in Water Level Control

## Research Objectives
Control water level in a 36.4-liter tank using reinforcement learning.
Maintain a predefined setpoint.
Test system with upscaling and downscaling setpoints.

## System Components
Control valve
Flow transmitter
Level transmitter
Tank with inflow and outflow
Programmable Logic Controller (PLC)
OPC server for communication

## Research Methodology
Simulate system in MATLAB Simulink.
Use DDPG reinforcement learning agent.
Evaluate performance based on rise time, settling time, maximum overshoot, and steady-state error.

## Results
Maximum overshoot: 1.9%
Maximum steady-state error: 1.29%

## Conclusion
DDPG reinforcement learning can effectively control water level in the tank.
Achieved good performance in terms of overshoot and steady-state error.
