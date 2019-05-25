# Swiftly
This project implements reinforcement learning to generate a self-driving car-agent with deep learning network to maximize its speed. The convolutional neural network was implemented to extract features from a matrix representing the environment mapping of self-driving car. The model acts as value functions for five actions estimating future rewards. 

The model is trained under Q-learning algorithm in a simulation built to simulate traffic condition of six-lane expressway. After continuous training for about 30 hours, the model learns the control policies for different traffic conditions and reaches an average speed 86 km/h (moderate traffic) compared to maximum speed of 110 km/h.
