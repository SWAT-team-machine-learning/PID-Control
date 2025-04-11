# PID-Control
Real-time Adaptive PID Control for DC Motor Speed Regulation using Neural Network-based Self-tuning

Abstract

This project proposes real-time adaptive PID control system for DC motor speed regulation, leveraging an Artificial Neural Network (ANN) for self-tuning of PID parameters. The ANN dynamically adjusts PID gains (Kp,Ki,Kd) in real time based on system metrics, improving performance. This hybrid approach combines classical control and machine learning, with the ANN trained online using recent data. A microcontrollerbased motor-sensor experimental setup was implemented to test the ANN-tuned PID control model. The activation of data training and the history buffer are scaled as percentages of the total runtime. However, results show that the ANN-tuned PID controller performs similarly to the conventional PID controller in the short term, but demonstrates effective convergence to the optimal PID gain values in the long term—particularly when the runtime and history buffer are sufficiently large.
