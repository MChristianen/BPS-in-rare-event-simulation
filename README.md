# Thesis

The most straightforward, however inefficient, way to estimate the probability of the rare event is a simple Monte Carlo method. Here we would draw $N$ i.i.d. samples $\{X_1,X_2,\ldots,X_N\}$ and the estimator for the probability of the rare event would be $\#\left\{i:\mathbb{P}(S(X_i))>L)\right\}/N$ for $i = 1,\ldots,N$. So, on average we would have to simulate $10^4$ samples to see only one occurrence of the rare event. 

There exist other methods to estimate this probability and the two most popular ones are importance sampling and splitting. In my thesis I will focus on the splitting method. I used "Simulation and Estimation of Extreme Quantiles and Extreme Probabilities" by Guyader as a starting point. They use the splitting method and a Random Walk Metropolis (RWM) algorithm to estimate the rare event probabilities. 

Instead of the standard RWM we thought that it would be beneficial to use another method to sample from a distribution, namely the Bouncy Particle Sampler. 


