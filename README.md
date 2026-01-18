FastSLAM Implementation in Webots (Particle Filter + EKF)

This project implements FastSLAM 1.0 for mobile robot localization and mapping in the Webots simulator.
The robot is controlled manually and estimates its pose using a particle filter, while building a map of landmarks using independent EKFs inside each particle.

Key features:

Odometry-based motion model with noise

Landmark-based sensing with simulated sensor noise

EKF updates for landmark position estimation

Importance weighting and stochastic universal resampling

Real-time visualization of particles, landmarks, and ground truth

The project demonstrates the core ideas behind FastSLAM: separating robot pose estimation (sampling) from landmark estimation (Kalman filtering) for efficient and scalable SLAM.

Demo Video: https://youtu.be/cSVXtl2pyXA
