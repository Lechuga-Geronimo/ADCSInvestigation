# ADCS-Investigation
In this project, I performed investigation work for the ADCS as part of my Research Internship activities. 

## Year: 2016.

I reviewed the state-of-art, founding how the ADCS is constitution: 

 * ADS: Attitude Determination System. Contains the sensors required to measure and estimate the attitude. Star trackers, Gyroscopes, Accelerometers, Magnetometers, IMU (generally composed by last three), Horizont sensors, LiDAR, GPS and equivalent (GNSS, GLONASS) and sensor fussion techniques; such Kalman Filter and signal processing.
 * 
 * ACS: Attitude Control Sytem. It's more likely a software system because, most of the times, it lacks of hardware. The ACS contains the control algorithms related to attitude. The most popular are H_infinity, PID + Neural networks, Linear Quadratic Regulator (LQR). This subsystem is also in charge of stabilization while deployment, commonly using the B-dot algorithm.
   
 * ADCS-HW: Attitude Determination and Control System - Hardware. It contains the actuators and their power drivers to perform the attitude regulation. The most popular are Reaction Wheels and Gyroscope Momentum Control (GMC) for rotation, Magnetorquers for momentum dumping and stabilization, Thrusters for altitude changes and rotation as well, and innovative actuators under current development such Omnisphere.
