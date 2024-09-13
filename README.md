# Frank-Wolfe-approach-to-boosting-algorithms
## Final Project for Optimization for Data Science Course, UniPD
### Project description
Boosting is a powerful ensemble algorithm designed to create a strong learner by combining multiple weak learners. It is particularly useful for tackling problems involving the optimization of the l1-norm soft margin. Various boosting algorithms have been developed to address this problem: 
- LPBoost is known for its fast convergence rate but can become computationally expensive in worst-case scenarios.
- ERLPBoost improves LPBoost by introducing entropy regularization, which balances the weighting of samples and mitigates overfitting on hard-to-classify examples.
  
The goal of this project is to enhance boosting algorithms by applying the Frank-Wolfe algorithm in combination with LPBoost, creating a hybrid framework known as MLPBoost (Modified LPBoost). This approach is based on the work of Mitsuboshi et al., as outlined in their paper _Boosting as Frank-Wolfe_. 
As tested on a real dataset, LPBoost retains the convergence guarantees of ERLPBoost while performing competitively with LPBoost in practical applications.
