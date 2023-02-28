# Vasicek-Model-Calibration-and-Pricing

The Vasicek model is a popular tool used to model the evolution of interest rates. It is described by the following Stochastic Differential Equation:
drt = κ(θ − rt)dt + σdWt.

It is a mean reverting process, with rate of mean reversion k, θ represents the mean, dt the time step, σ the Standard Deviation and dWt are the increment of a Brownian Motion.

Calibration:
Calibrating the Vasicek model to the interest rate curve on a specific date provides the optimal parameters that best fit the observed market data. In turn, this information can be used to simulate the risk-neutral dynamics of interest rates and price financial instruments.

ZCB Pricing:
Zero-coupon bonds (ZCBs) are financial instruments that pay no periodic coupon payments and instead pay the entire return at maturity. The price of a ZCB can be determined using the Vasicek model and Monte Carlo simulation.
The steps involved in pricing a ZCB using Monte Carlo simulation are as follows: 
1. Define the simulation parameters: Define the length of the simulation period, the number of simulations to be performed, and the time step size.

2. Generate random interest rate paths: Generate random interest rate paths based on the calibrated Vasicek model parameters and the defined simulation parameters.

3. Calculate the ZCB price: For each of the generated interest rate paths, calculate the ZCB price at maturity by discounting the face value with the simulated interest rates.

4. Analyze the results: Analyze the results of the simulation to determine the expected value and the distribution of the ZCB price at maturity.
