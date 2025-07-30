# Probability Foundations in R – Applied Statistics for Analysts

This Quarto notebook introduces the fundamentals of probability theory using R. It emphasizes computational thinking, simulation, and probabilistic reasoning—skills essential for developing a deeper understanding of statistical inference, modeling assumptions, and decision-making under uncertainty.

## Purpose

To build practical fluency in probability by applying core concepts in R. This notebook bridges theoretical probability and real-world data analysis using simulations, probability distributions, and visualizations to reinforce key ideas.

## Technologies Used

- **R** – Statistical computing language
- **Quarto** – Reproducible notebook environment
- **Base R + ggplot2** – Probability modeling and visualization

## Topics Covered

### Probability Theory Basics

- Definition and interpretation of probability
- Sample spaces and events
- Complement, union, and intersection of events
- Conditional probability and independence

### Simulation as a Problem-Solving Tool

- Monte Carlo methods for empirical probability estimation
- Use of `replicate()` and `sample()` to simulate draws from finite populations
- Estimating long-run frequencies through random experiments

### Discrete Distributions

- Exploration of:
  - Bernoulli and Binomial distributions (`rbinom()`)
  - Geometric and Negative Binomial
  - Hypergeometric and Poisson
- Calculating exact and cumulative probabilities with `dbinom()`, `pbinom()`, etc.
- Visualizing PMFs with `barplot()` and `ggplot2`

### Continuous Distributions

- Introduction to:
  - Uniform and Normal distributions
  - Exponential and Gamma (if applicable)
- Generating random variables with `rnorm()`, `runif()`, `rexp()`
- Using `dnorm()`, `pnorm()`, `qnorm()` for analytic solutions

### Applications and Insights

- Realistic use-cases such as quality control, A/B testing frameworks, system reliability, and customer behavior modeling
- Approximating probabilities using the Central Limit Theorem
- Communicating uncertainty through plots and probability statements

## Analytical Value

Understanding probability is critical for:

- Designing and interpreting experiments
- Validating modeling assumptions
- Building probabilistic machine learning models (e.g., Naive Bayes, Bayesian Networks)
- Developing simulation-based forecasting or risk assessment models

## Getting Started

To run the notebook:

1. Open the `.qmd` file in RStudio.
2. Make sure required packages (e.g., `ggplot2`) are installed:
   ```r
   install.packages("ggplot2")
