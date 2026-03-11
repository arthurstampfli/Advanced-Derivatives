# Advanced Derivatives 

This repository contains a series of assignments from the Advanced Derivatives  course at EPFL.  
The projects focus on the pricing, calibration, and numerical implementation of derivative models** used in modern quantitative finance.

The implementations combine analytical derivations, stochastic modeling, and numerical methods** including Monte Carlo simulation and finite-difference schemes.

---

# Topics Covered

The projects cover several core topics in quantitative derivatives pricing:

- Jump-diffusion option pricing
- Implied volatility and implied distributions
- Copula-based dependence modeling
- Stochastic volatility models (SABR)
- Interest rate derivatives
- Monte Carlo simulation
- Finite-difference methods for PDE pricing
- Bermudan swaption pricing

---

# Assignments Overview

## Assignment 1 – Jump-Diffusion Option Pricing

Pricing European call options under a **jump-diffusion process** and computing the resulting **implied volatility smile**.

Main elements:
- Derivation of option pricing formula under jump-diffusion dynamics
- Numerical implementation of the infinite series representation
- Computation of implied volatility for different strikes and maturities
- Analysis of the implied volatility smile

---

## Assignment 2 – Implied Distributions and Copula Simulation

Extraction of **risk-neutral distributions from option prices** and pricing of exotic payoffs via simulation.

Main elements:
- Recovery of the implied distribution from option prices
- Simulation of correlated asset prices using a **Gaussian copula**
- Monte Carlo pricing of exotic payoffs
- Estimation of pricing error using standard error

---

## Assignment 3 – SABR Volatility Model Calibration

Calibration of a **stochastic volatility model (SABR)** to market implied volatility data.

Main elements:
- Implementation of the SABR implied volatility approximation
- Calibration of model parameters using numerical optimization
- Comparison between model-implied volatility and market data
- Visualization of implied volatility smiles and surfaces

---

## Assignment 4 – Interest Rate Derivatives (Vasicek Model)

Pricing an option on a coupon-paying bond under the **Vasicek short-rate model**.

Main elements:
- Analytical bond pricing under Vasicek dynamics
- Derivation of the pricing formula for bond options
- Numerical solution of the pricing PDE
- Implementation of finite-difference schemes:
  - Explicit method
  - Crank–Nicolson method
- Analysis of convergence and numerical stability

---

## Assignment 5 – Bermudan Swaption Pricing

Monte Carlo pricing of a **Bermudan swaption** under a forward rate model.

Main elements:
- Simulation of forward interest rates
- Construction of correlated Brownian motions
- Monte Carlo simulation of swap values
- Determination of optimal exercise thresholds
- Estimation of option price from simulated paths


