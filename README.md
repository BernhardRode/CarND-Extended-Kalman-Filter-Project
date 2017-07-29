# Extended Kalman Filter Project Starter Code
Self-Driving Car Engineer Nanodegree Program

# Build instructions

1. mkdir build
2. cd build
3. cmake ..
4. make
5. ./ExtendedKF

or just execute

1. ./run.sh

INPUT: values provided by the simulator to the c++ program

["sensor_measurement"] => the measurement that the simulator observed (either lidar or radar)

OUTPUT: values provided by the c++ program to the simulator

["estimate_x"] <= kalman filter estimated position x
["estimate_y"] <= kalman filter estimated position y
["rmse_x"]
["rmse_y"]
["rmse_vx"]
["rmse_vy"]

# Outputs

Starting with Udacity's ["Extended kalman filter" starter code](https://github.com/udacity/CarND-Extended-Kalman-Filter-Project). I've first added the functions, we learned during the lessons to prepare tools and the basic kalman filter.

Following that , I've finished my implementation in FusionEKF.cpp with:
* Initialization of variables and matrices
* Initialization of the EKF
* Predict F and Q matrices when new measurements arrive
* Update EKF using received sensor data (either LIDAR or Radar)

The outputs for estimation is in [output.txt](https://github.com/BernhardRode/CarND-Extended-Kalman-Filter-Project/blob/master/outputs/output.txt) file.