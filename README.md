# RL for DDPG in Water Level Control

## Research Objectives
1. Control water level in a 36.4-liter tank using reinforcement learning.
2. Maintain a predefined setpoint.
3. Test system with upscaling and downscaling setpoints.

## System Components
1. Control valve
2. Flow transmitter
3. Level transmitter
4. Tank with inflow and outflow
5. Programmable Logic Controller (PLC)
6. OPC server for communication

## Research Methodology
1. Simulate system in MATLAB Simulink.
2. Use DDPG reinforcement learning agent.
3. Evaluate performance based on rise time, settling time, maximum overshoot, and steady-state error.

## Results
1. Maximum overshoot: 1.9%
2. Maximum steady-state error: 1.29%

## Conclusion
DDPG reinforcement learning can effectively control water level in the tank and achieved good performance in terms of overshoot and steady-state error.
