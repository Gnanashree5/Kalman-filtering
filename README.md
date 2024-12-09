# Kalman Filtering

## Overview

The **Kalman Filter** is a powerful algorithm used to estimate the state of a system in the presence of uncertainty or noise. It is widely used in engineering fields such as robotics, control systems, and signal processing.

---

## Key Features of Kalman Filtering

1. **Prediction Step**: Estimates the future state based on the current state and a model of the system.
2. **Update Step**: Refines the prediction using observed measurements.
3. **Recursive Nature**: Updates the state and uncertainty iteratively, making it computationally efficient.

---

## Applications

- Object tracking (e.g., cars, airplanes, and satellites).
- Sensor fusion (combining data from multiple sensors).
- Reducing noise in time-series data.

---

## Code Description

### Kalman Filter Implementation

1. **Prediction**:
   - Estimates the next state using the system's dynamics.
   - Updates the covariance matrix for uncertainty estimation.
2. **Measurement Update**:
   - Adjusts the prediction with measurements using the Kalman Gain.

### Simulated Data
The code simulates noisy measurements of an object moving in 1D. The Kalman Filter estimates the true position and velocity from these noisy measurements.

---
<h2>Acknowledgements</h2>
<p>This notebook was done under guidance of  <a href="https://github.com/Victor-Ikechukwu">Dr. Agughasi Victor Ikechukwu</a></p>
