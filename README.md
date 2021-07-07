# Kalman-filter
Here, I have modeled a Kalman Filter on python

# Motivation
I am very fortunate that I came across the academic course on Estimation and Information Fusion at RWTH university. Here I learnt the the algorithm behind Kalman filter, which I wanted to understand for a while. I was mostly curious to know how to see through the random noise (uncertainty) in the measurements and work out a method of reliable tracking in an optimal fashion. 

# Idea of the Kalman Filter
The readings that sensors produce are close to the true value of the parameter that one is interested in,but they won't equate to the parameters.
This can be attributed to our approximation of measurement function, random process noise etc. 
So the problem statement is if we cant trust the measurements from our sensors, we have to figure out a method to track parameters, such that we are able to trust its results more than our sensor readings.

Kalman filter is an elegant solution to this problem. It's an algorithm that performes Bayes optimal dynamic state estimation. It is based on a dynamic model for Predictions and a measurement model for update. It leads to an optimal Minimum Mean Squared Error Estimation for linear dynamic systems. 

Fun fact: Rudolf Kálmán who co invented this algorithm faced a lot of criticism initially. He was forced to publish his results in  Mechanical engineering rather than Electrical or systems Engineering. 

# code
The code is an ipython file and I have tried to present descriptions/ mathematical formulations along the code cells. 

# What is next
Since Kalman filter only performs well on linear systems. I will build Extended and Unscented Kalman filters in the future. 
