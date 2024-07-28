# Practice Problem 1.2

## Problem

Given that the total charge entering a terminal is $q=(20-15t-10e^{-3t})$ mC, calculate the current at $t=1.0$ s.

## Solution

Electric current is the time rate of change of charge. Mathematically the relationship between current $i$, charge $q$, and time $t$ is:

$$i=\frac{dq}{dt}$$

We know the charge because it is given in the problem, but to get the current we need to calculate the derivative of the charge:

$$\frac{dq}{dt}=\frac{d}{dt}(20-15t-10e^{-3t})=0-15-10e^{-3t}(-3)=30e^{-3t}-15$$

We now know how the current varies over time. It is stated in the problem that we are looking for the current at the time point $t=1.0s$. We will hence plug in this value in our formula from above:

$$i=30e^{-3t}-15=30e^{-3\times1.0}-15=30e^{-3}-15$$

To get the current as a single value we use an scientific calculator:

$$i=30e^{-3}-15\approx-13.506$$

Note that since the unit for the charge $q$ is in mC so will the unit for the current $i$ be in mA.

### Answer

$-13.506$ mA
