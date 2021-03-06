# SLAM

In this project, algorithms were developed to allow a robot to implement the Simultaneous Localization and Mapping (SLAM) technique in an indoor environment. For this, odometry, inertial and range measurements that had been previously collected using a mobile robot were used. The sensors the robot used to collect these measurements include wheel encoders, a Light Detection and Ranging sensor (LIDAR), and an Inertial Measurement Unit (IMU).

The SLAM approach was implemented using a Particle Filter (PF) with systematic resampling. Maps of different environments were created using first encoder and LIDAR data using the dead-reckoning technique and without a particle filter, and afterwards the full SLAM algorithm with a particle filter. A clear improvement in the results can be found after adding the particle filter. 

The report and videos of the resulting maps can be found in this repository. Due to privacy policy, the code is not available to the public. Feel free to drop me a message if you want to learn more about the code implementation! 
