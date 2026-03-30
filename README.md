# Observer-Based Control of a Rotary Inverted Pendulum

Control systems project focused on stabilizing a rotary inverted pendulum using state feedback and a Luenberger observer.

---

## Overview
This project models and controls a rotary inverted pendulum, an inherently unstable nonlinear system.

The system is linearized and represented in state-space form. Since not all states are measurable, a Luenberger observer is used to estimate the full state vector. These estimates are then used in a state feedback controller to stabilize the pendulum in the upright position.

---

## Methods
- Derived nonlinear dynamics using Euler-Lagrange equations  
- Linearized system around upright equilibrium  
- Designed state-space model (4 states)  
- Verified controllability and observability  
- Designed:
  - State feedback controller (pole placement)  
  - Luenberger observer  

---

## Tools
- MATLAB  
- Simulink  

---

## Results
- Pendulum stabilized at upright position (θ ≈ 0°)  
- Successful response to step and sine inputs  
- System remains stable under disturbances  
- Observer accurately estimates unmeasured states  

---

## Notes
- Initial instability due to observer startup conditions  
- System requires proper initialization for best performance
