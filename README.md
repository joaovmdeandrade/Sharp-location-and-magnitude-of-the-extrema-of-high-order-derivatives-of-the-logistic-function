# Logistic Derivative Extrema — Reproducibility Code

This repository contains the numerical reproduction code for the paper

**“Sharp location and magnitude of the extrema of high-order derivatives of the logistic function”**  
João Victor M. de Andrade and Leonardo Santos da Cruz.

The script uses arbitrary-precision arithmetic to reproduce the numerical
results reported in the paper, including:

- the location of the positive extrema of even-order logistic derivatives;
- the sharp second-order asymptotic correction for the extremum location;
- normalized uniform norms and their asymptotic correction;
- numerical audits of the explicit constants used in the proofs;
- checks for the low-order cases \(n=2,4,6,8\);
- comparisons with Reimer's exact Euler--Frobenius roots;
- the tables and figure appearing in the manuscript.

The numerical computations are provided for reproducibility and illustration;
the proofs in the paper do not depend on the code.
