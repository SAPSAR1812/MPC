# MPC
Please refer to the 'Quadruple_Tank_Process' file for a summary of the work. 

Two parts to the project: 
1) The implementation of state estimation methods (Kalman Filter and Particle Filter). Compared the convergence and accuracy of both methods. The true measurements 
are available in file 'Measurements.xlsx', which were used to shrink the covariance matrix for both filters. Results required were graphs showing the convergence
of the four states and the plots between innovations & residuals with time. 

2) Implementing MPC to control levels: Used estimated states from a Kalman filter. Switched controlled variables and measured variables to see the differences in
convergence. Next, we set constraints to the input, rate of change of input and output to see their impact on controller performance. Decreased overshoot by 10%
by increasing prediction horizon, decreasing control horizon and decreasing control penalty. 

