### README: Extended Kalman Filter Localization

#### Overview
This script uses the Extended Kalman Filter (EKF) to localize a simulated vehicle along a course, 
combining sensor data, vehicle dynamics, and path-following algorithms. 
The simulation is visualized with `GlobalXYVisualizer`.

### Features
1. Course Generation: Smooth course creation using cubic splines.
2. Vehicle Simulation: Simulates a four-wheel vehicle with state management.
3. Control: Pure Pursuit controller for path following.
4. Sensors: GNSS simulation with configurable noise.
5. **Localization: EKF for accurate position and orientation estimation.
6. Visualization: 2D simulation display.

### Usage
- Run the simulation:
  ```bash
  python extended_kalman_filter_localization.py
  ```
- To disable the plot (e.g., for testing), set `show_plot` to `False`.
