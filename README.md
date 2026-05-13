# Distributions of Brownian Motion & Continuous-Time Stochastic Processes

**Authors:** Tristan Endo, Professor Robert Webber\n
**Institution:** University of California, San Diego\n
**Year:** 2025\n

📄 [View Paper](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/Tristane028/Brownian-Motion-Distributions-Simulation/main/Distributions_of_Brownian_Motion_and_Continuous_Time_Stochastic_Processes.pdf)

## Overview

This project examines the distributions of Brownian motion and continuous-time stochastic processes. We investigate the distribution of peaks in fractional Brownian motion and derive the conditional distributions of standard Brownian motion and the Ornstein-Uhlenbeck process. The goal of these experiments was to see how the Hurst parameter affects the distribution of the maximum and how conditioning on boundary values changes the behavior of these processes.

## Contents

- Numerical investigation of the distribution of peaks in fractional Brownian motion on [0,1] for varying Hurst parameter H
- Derivation of the conditional distribution of standard Brownian motion given W(0)=0 and W(1)=x1, known as the **Brownian Bridge**
- Derivation of the conditional distribution of the Ornstein-Uhlenbeck process given X(0)=x0 and X(1)=x1, known as the **Ornstein-Uhlenbeck Bridge**

## Key Results

- For H < 0.5, the fractional Brownian motion is negatively correlated — the process is more likely to reverse direction, resulting in smaller overall maxima and a more spread out distribution.
- For H = 0.5, the process reduces to standard Brownian motion with no correlation between increments.
- For H > 0.5, the process is positively correlated — the process tends to follow its current trend, resulting in much larger maxima and a more concentrated distribution.
- The conditional distribution of W(t) given W(1) = x1 is a Gaussian process with mean tx1 and covariance min(s,t) - st, which is the standard Brownian Bridge.
- The conditional distribution of the Ornstein-Uhlenbeck process given both endpoints is Gaussian and mean-reverting between x0 and x1, known as the Ornstein-Uhlenbeck Bridge.

## Background

Brownian motion was first observed by Robert Brown in 1827 and later given a rigorous mathematical foundation by Einstein and Wiener. Fractional Brownian motion extends the standard model by introducing dependent increments controlled by the Hurst parameter. The Ornstein-Uhlenbeck process is a mean-reverting Gaussian process commonly used to model physical and financial systems.

## References

- Robert M. Gray. *Probability, Random Processes, and Ergodic Properties.* Springer, 2009.
- Bernt Øksendal. *Stochastic Differential Equations.* Springer, 2003.
- Benoit B. Mandelbrot and John W. Van Ness. *Fractional Brownian Motions, Fractional Noises and Applications.* SIAM Review, 1968.
