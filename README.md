# DakotaPractice
An attempt at using Dakota for parameter optimization.

<p> In this folder I have a MATLAB code that optimizes both parameters (surface temperature and years elapsed) so that I would know if Dakota was working correctly and matching the MATLAB chi-squared minimized parameters...unfortunately I have yet to get Dakota to work at all despite many hours of trying different things. The working MATLAB only code is called HeatDiffusion1DParameterOptimization.m, it takes a little while to run because I have it doing a total of 10,000 iterations to find the best parameter values. Feel free to decrease the number of runs for a speedier (but less precise) search. </p>
<p></p>
<p> For the Dakota part, I started by trying to get Dakota to work with MATLAB and did not succeed. I cannot figure out at all how to get MATLAB and Dakota to talk to each other. </p>
<p> I am now in the process of translating my MATLAB code to python and seeing if it would work with Dakota that way. I am not finished with it, and do not know if I will be finished by class on Wednesday. </p>
<p> I think conceptually I understand what Dakota should be doing, but I do not feel I have the coding practice or training required to successfully implement it yet.</p>
