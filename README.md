# Stochastic Processes: Gaussian Processes and Stochastic Sampling

A computational project exploring **Gaussian processes, Bayesian inference, Markov chain Monte Carlo, and Langevin dynamics**, developed as part of the *Stochastic Processes* course at **Sharif University of Technology**.

**Authors:** Ali Javidan Pak, Radmehr Fathi
**Instructor:** Dr. Peyvandi

## Overview

The project studies several computational methods for stochastic modeling, inference, and sampling:

* Gaussian-process priors and covariance kernels
* Gaussian-process regression
* Bayesian inference of kernel hyperparameters using Metropolis–Hastings
* Langevin dynamics and stochastic sampling

The implementations are developed from the underlying mathematical formulations and illustrated through numerical experiments in Python.

## Topics

### 1. Gaussian Processes

The notebook introduces Gaussian-process priors using different covariance kernels, including:

* Radial Basis Function (RBF) kernel
* Brownian-motion kernel

Covariance matrices are constructed and sampled to visualize realizations from the corresponding Gaussian-process priors.

### 2. Gaussian-Process Regression

Gaussian-process regression is used to obtain posterior distributions conditioned on observed data.

The implementation calculates:

* Posterior mean
* Posterior covariance
* Posterior predictive samples

### 3. Bayesian Hyperparameter Inference

The kernel length scale is treated as an unknown parameter and inferred using Bayesian methods.

The notebook implements:

* Gaussian-process marginal likelihood
* Metropolis–Hastings sampling
* Burn-in and posterior analysis

This illustrates how stochastic simulation can be combined with Bayesian inference for model parameters.

### 4. Langevin Dynamics

The project also investigates Langevin dynamics as a method for sampling from probability distributions.

The continuous Langevin equation is discretized using the **Euler–Maruyama method**, leading to the **Unadjusted Langevin Algorithm (ULA)**.

The algorithm is applied to a bimodal Gaussian-mixture target distribution, and the resulting samples are compared with the target density.

## Implementation

The project is implemented in **Python** using standard scientific-computing and visualization libraries.

The complete work is contained in:

`stochastic_processes.ipynb`

## Purpose

The project combines theoretical concepts from stochastic processes with computational experiments, providing practical experience with **Gaussian-process modeling, Bayesian inference, MCMC methods, and stochastic differential equations**.
