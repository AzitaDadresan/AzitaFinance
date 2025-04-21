
# Financial Models in Python

This repository contains implementations of various financial models using Python and Jupyter Notebooks. Each model is designed to simulate key financial processes and visualize their behavior.

## Notebooks

1. **[Black-Scholes Option Pricing](Complete_Black_Scholes.ipynb)** – Closed-form pricing for European call/put options, complete with Greeks and visualizations.
2. **[Binomial Model Pricing](binomial_option_pricing.ipynb)** – A binomial tree model for option pricing.
3. **[Euler-Maruyama Simulation](euler_maruyama.ipynb)** – A numerical method to approximate solutions to stochastic differential equations.
4. **[GBM Monte Carlo Simulation](monte_carlo_simulation.ipynb)** – Monte Carlo simulation of Geometric Brownian Motion for option pricing.
5. **[Vasicek Interest Rate Model](vasicek_simulation.ipynb)** – Mean-reverting stochastic model for interest rates.
6. **[Finite Difference Methods](finite_difference_methods.ipynb)** – Numerical solutions for PDEs in option pricing (explicit, implicit, Crank-Nicolson).
7. **[Implied Volatility Estimation](implied_volatility.ipynb)** – Estimating implied volatility using root-finding techniques on Black-Scholes formula.

## How to Run

1. Clone the repository:
   ```bash
   git clone <your-github-repo-url>
   cd <your-repo-folder>
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open any notebook to explore simulations, visualizations, and pricing models.

## Dependencies

```bash
pip install numpy pandas matplotlib scipy
```
(Optional: Install Jupyter if not already available.)
```bash
pip install notebook
```

## License

Open for educational use and individual research. Contributions welcome!
