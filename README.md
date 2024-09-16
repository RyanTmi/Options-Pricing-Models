# Option Pricing Models

This repository provides an in-depth analysis and comparison of two foundational models in option pricing: the **Black-Scholes** Model and the **Heston** Model.
The project involves theoretical insights, practical implementation, and visual analysis to showcase how these models perform in real-world financial markets.

## Project Overview

In this project, we explore two major frameworks for option pricing:

1. **Black-Scholes Merton Model**:
A classical option pricing model assuming constant volatility, widely used for European options.
2. **Heston Model**:
A stochastic volatility model that generalizes the Black-Scholes framework by allowing volatility to be random and dynamic, better capturing real-world market behaviors.

The notebooks in this project walk through each model, from theoretical foundation to practical implementation, including:

- Calculating historical volatility and implied volatility.
- Simulating stock prices using Geometric Brownian Motion.
- Pricing options using both Black-Scholes and Monte Carlo simulation.
- Analyzing volatility smiles and surfaces.
- Implementing stochastic volatility with the Heston model.

---

## Future Updates

This project currently focuses on foundational models of option pricing, but there are several advanced topics and enhancements that we plan to explore in future updates:

### 1. Option Greeks Calculation

The next step is to incorporate the Greeks—key risk measures that are derived from the pricing models:

- **Delta**: Sensitivity of the option price to changes in the underlying asset’s price.
- **Gamma**: Rate of change of Delta with respect to the underlying asset’s price.
- **Vega**: Sensitivity of the option price to volatility.
- **Theta**: Sensitivity of the option price to time decay.
- **Rho**: Sensitivity of the option price to changes in interest rates.

These will provide deeper insights into risk management and options trading strategies.

### 2. Delta Hedging Simulation

Implementing a delta hedging strategy to demonstrate how traders can neutralize risk by adjusting their portfolios in real-time as the market moves.
This section will involve:

- Dynamic hedging over time using Delta.
- Tracking portfolio value and hedging performance over the life of the option.

### 3. Jump-Diffusion Models

Explore jump-diffusion models (e.g., **Merton’s** model) to account for sudden, large movements in asset prices.
This will help in modeling real-world phenomena like earnings announcements or macroeconomic shocks.

### 4. American Options and Early Exercise

Currently, we focus on **European options**, which can only be exercised at expiration.
Future updates will explore **American options**, which can be exercised at any time before expiration.
We’ll implement numerical methods like binomial trees or finite difference methods for pricing these options.
