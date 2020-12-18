#stochastic-processes-matlab

#summary of Euler-Maruyama
#dX = a(x,t)dt + b(x,t)dW
#X(i+1,:) = X(i,:) + a(i, t)dt + b(i,t)sqrt(dt)


define model parameters

nsteps = 200; %choice
npaths = 2000; %choice
T = 1; dt = T/nsteps; t = 0:dt:T; %choice 
X0 = 0.05 # depending on what model you are using you may or may not need to define an initial value

some models can be done with only array operations and some can't. GBM is a combination of both. 










