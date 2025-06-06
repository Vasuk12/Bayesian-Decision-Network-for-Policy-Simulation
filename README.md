# Bayesian Decision Network for Policy Simulation

This project demonstrates causal effect estimation and policy simulation by combining causal inference techniques with Bayesian network modeling. It showcases skills in causal effect estimation, refutation analyses, sensitivity checks, and probabilistic modeling — key competencies sought in data science and analytics roles.

## Objective

Estimate the causal impact of treatment variables on outcomes and validate results through rigorous refutation and sensitivity analyses, followed by building Bayesian network models for probabilistic inference on multi-variable causal structures.

## Tools & Libraries

- Python 3.x  
- DoWhy — Causal inference framework  
- pgmpy — Bayesian network modeling  
- NetworkX, Matplotlib — Graph visualization  
- Pandas, NumPy — Data manipulation  

## Dataset Overview

- Observational data with treatment, outcome, and confounding variables  
- Directed Acyclic Graph (DAG) defining causal relationships  

## Methodology

- **Causal Effect Estimation:** Backdoor adjustment with linear regression  
- **Refutation & Sensitivity Analyses:** Bootstrap, placebo treatment, subset sampling, and unobserved confounders refuters  
- **Bayesian Network Modeling:** Construct discrete Bayesian networks with conditional probability tables  
- **Visualization:** DAG and inference results visualization  

## Key Results

- Estimated causal effect size: -0.0175  
- Robustness confirmed via 100+ bootstrap simulations  
- Refutation p-values consistently > 0.85 indicate stability against hidden confounding  
- Bayesian networks built with 5 nodes and 6 edges enable probabilistic inference for policy simulation  

## Business Recommendations

- Use validated causal estimates to guide policy decisions  
- Leverage Bayesian models for probabilistic scenario analysis  
- Continuously monitor model sensitivity to potential unobserved confounders  

## Next Steps

- Extend Bayesian models to handle continuous variables  
- Incorporate dynamic or hierarchical Bayesian networks  
- Develop interactive dashboards for causal graph and inference exploration  

## Skills Demonstrated

- Causal inference & effect estimation  
- Robust refutation and sensitivity analyses  
- Bayesian network construction & probabilistic reasoning  
- Data visualization and storytelling  
