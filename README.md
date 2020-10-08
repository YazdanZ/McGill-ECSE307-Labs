# McGill-ESCE307-Labs
![](https://img.shields.io/badge/-Octave-informational?style=for-the-badge&logo=Octave&logoColor=white&color=0790C0) 
![](https://img.shields.io/badge/-MATLAB-informational?style=for-the-badge&logo=Mathworks&logoColor=white&color=F0652F) 



This repository contains the Lab component of ESCE307-Linear Systems and Control.<br/>
<br/>
As a result of studying from home because of the COVID-19 pandemic, labs for linear systems and control are done using MATLAB. The goal of these labs being simulating systems and controls without hardware equipment. 
<br/>
<br/>
Each Lab contains : 
* a Lab handout (such as `Lab01.pdf`)
* a Lab LiveScript (such as `Lab01.mlx`)
* a Lab Report in LaTeX and a Pdf output (such as `Lab01-Report.pdf`)
* a `.mat` data file containing environment variables
<br/>

## [Lab1](https://github.com/Unixado/McGill-ESCE307-Labs/tree/master/Lab1)
This Lab was an introduction to common MATLAB functions that will be used in the following labs. 


Some areas of study were:
* Arrays and Matrices
* Generating array to model Discrete-Time signals
* Logical operations in modeling signals
* Plotting CT and DT signals
* Symbolic variables and functions
* Saving/Loading data 
* Simplifying expressions  
* Computing Laplace and Inverse Laplace Transforms

[Lab handout](https://github.com/Unixado/McGill-ESCE307-Labs/blob/master/Lab1/Lab01.pdf)<br/>
[Lab Report](https://github.com/Unixado/McGill-ESCE307-Labs/blob/master/Lab1/Lab01-Report.pdf)<br/>
[MATLAB Livescript](https://github.com/Unixado/McGill-ESCE307-Labs/blob/master/Lab1/Lab01.mlx)<br/>


## [Lab2](https://github.com/Unixado/McGill-ESCE307-Labs/tree/master/Lab2)
This Lab was about analyzing second order systems by their impulse response and transfer functions. Some activities of this lab were plotting step responses and identifying characteristics of transient responses. An open-loop unstable system was introduced that had to be stabilized by adding a gain (controller) and a feedback to the system, transforming it into a closed-loop system. The stabilized closed-loop system was then approximated using dominant pole approximation and results were analyzed. 


Some other areas of study were: 
* Modeling Linear Time Invariant (LTI) systems 
* Different ways of defining transfer functions 
* Using the Zero-pole-gain model (zpk)
* Determining poles and zeros of transfer functions 
* Plotting impulse and step responses
* Interconnection of systems

[Lab handout](https://github.com/Unixado/McGill-ESCE307-Labs/blob/master/Lab2/Lab02.pdf)<br/>
[Lab Report](https://github.com/Unixado/McGill-ESCE307-Labs/blob/master/Lab2/Lab02-Report.pdf)<br/>
[MATLAB Livescript](https://github.com/Unixado/McGill-ESCE307-Labs/blob/master/Lab2/Lab02.mlx)<br/>

## [Lab3](https://github.com/Unixado/McGill-ESCE307-Labs/tree/master/Lab3)
In this lab, the transfer function for a virtual DC motor is identified. Using MATLAB, the DC motor is being interacted with to generate input/output data. This data is then used to find an approximation of the transfer function associated to the virtual DC motor. The approximation is then validated and slightly improved by finding and examining the RMSE. Model parameters of the DC motor such as the motor viscous friction constant are then detected using the properties of its time response. 


Additional areas of study were: 
* Interacting with virtual systems in MATLAB
* Data collection to determine the step response
* Data analysis in order to find the transfer function of a system
* Simulating the output of a linear system given an input
* Calculating the root mean squared error (RMSE) of a simulation or a prediction

[Lab handout](https://github.com/Unixado/McGill-ESCE307-Labs/blob/master/Lab3/Lab03.pdf)<br/>
[Lab Report](https://github.com/Unixado/McGill-ESCE307-Labs/blob/master/Lab3/Lab03-Report.pdf)<br/>
[MATLAB Livescript](https://github.com/Unixado/McGill-ESCE307-Labs/blob/master/Lab3/Lab03.mlx)<br/>
[Virtual DC motor](https://github.com/Unixado/McGill-ESCE307-Labs/blob/master/Lab3/VirtualMotor.m)<br/>

## [Lab4](https://github.com/Unixado/McGill-ESCE307-Labs/tree/master/Lab4)
In this lab, different simulation experiments were run to track a desired reference signal with a simulated DC Motor. This was first done by running an open-loop experiment, then using the state feedback to control the angular velocity of DC motor. The lab was done using state space representation with the objective being to track a reference signal ωref while satisfying the following requirements:

* Overshoot less than 10%.
* 5%-settling time less than 0.2 seconds.
* Steady state gain of 1 ± 5%.


Additional areas of study were: 
* State feedback controller design in MATLAB
* Simulating state-space representation models in MATLAB
* Eigenvalue calculations
* DC gain calculations

[Lab handout](https://github.com/Unixado/McGill-ESCE307-Labs/blob/master/Lab4/Lab04.pdf)<br/>
[Lab Report](https://github.com/Unixado/McGill-ESCE307-Labs/blob/master/Lab4/Lab04-Report.pdf)<br/>
[MATLAB Livescript](https://github.com/Unixado/McGill-ESCE307-Labs/blob/master/Lab4/Lab04.mlx)<br/>


