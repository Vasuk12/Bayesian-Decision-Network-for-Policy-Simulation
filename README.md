# Bayesian-Decision-Network-for-Policy-Simulation

Overview
This project implements a causal inference pipeline combining causal effect estimation, robust refutation analyses, and Bayesian network modeling to simulate and analyze policy impacts. The workflow leverages real-world data to identify causal relationships and validate them through advanced statistical methods.

Key Features
Causal Effect Estimation: Estimated average treatment effects using backdoor adjustment with linear regression, yielding an effect size of approximately -0.0175.

Robustness Validation: Conducted over 100 bootstrap simulations to ensure stability and reliability of causal estimates.

Sensitivity and Refutation Analyses: Applied placebo treatments, subset data checks, and hidden confounder modeling, with consistent p-values > 0.85 confirming robustness.

Bayesian Network Modeling: Built discrete Bayesian network models using conditional probability tables on multi-variable causal graphs for probabilistic inference and decision support.

Technical Details
Python libraries: DoWhy, pgmpy, NetworkX, matplotlib

Causal model specified via Directed Acyclic Graph (DAG) syntax

Bootstrap refutation methods implemented for causal estimate validation

