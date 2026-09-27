# BSc-Mathematical-Computational-Projects

This repository collects coursework notebooks from university studies, covering statistics, cosmology, stochastic processes, and numerical methods for differential equations. Each notebook is self-contained and combines theoretical derivations with numerical/computational implementations in Python.

## Contents

### `CStatsTutorial.ipynb`
**Topic**: Point estimation in statistics.
Covers sufficient statistics and point estimators (Maximum Likelihood and Method of Moments). Includes a worked example deriving and comparing ML and MoM estimators, Monte Carlo simulation of their sampling distributions, and analysis of how estimator MSE scales with sample size.

### `Cosmology_FRWL_universes.ipynb`
**Topic**: Numerical cosmology — FRWL universe models.
Numerically solves the Friedmann equation for the scale factor a(t) under various cosmological compositions (matter-dominated, Lambda-dominated, flat and non-flat universes, and negative-Lambda scenarios). Compares numerical solutions against known analytical results (e.g., Einstein-de Sitter and de Sitter universes) and discusses the physical interpretation of each case.

### `Computing_Variational_distance.ipynb`
**Topic**: Stochastic processes — Markov chain mixing.
Models a card-shuffling process as a Markov chain, derives its transition matrix, and computes the total variation distance between the chain's distribution and its stationary distribution over time. Includes a simulation of convergence to the uniform stationary distribution and an estimate of the associated mixing rate.

### `Beta-Method.ipynb`
**Topic**: Numerical methods for ODEs — the beta-method.
Implements and analyses the beta-method (a generalised theta-method) for solving scalar and systems of initial value problems (IVPs). Investigates stability (A-stability) and accuracy (order of convergence) for beta = 0, 0.5, and 1, corresponding to Forward Euler, the midpoint/trapezoidal method, and Backward-Euler. Applies the method to a two-body gravitational dynamics problem and a nonlinear ODE system, including a Lyapunov stability analysis.

## Notes

- These notebooks were developed as homework/tutorial assignments and are presented largely as originally submitted, including inline discussion answers to assignment questions.
- Each notebook is self-contained; there are no shared internal dependencies between them.
- Standard scientific Python libraries are used throughout (e.g., NumPy, SciPy, Matplotlib).
