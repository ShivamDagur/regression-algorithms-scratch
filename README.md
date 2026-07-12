Regression Algorithms from Scratch

This repository is a hands-on exploration of regression algorithms, built entirely from scratch in Python — without relying on machine learning libraries like scikit-learn. The goal isn't just to get a working model, but to genuinely understand what's happening under the hood: the math, the derivations, and the optimization logic that power each algorithm.

Most tutorials teach you to call `.fit()` and `.predict()` without ever explaining why those functions work. This project takes the opposite approach — every algorithm here is implemented line by line, starting from the underlying equations, so that each step (cost function, gradient computation, optimization, or closed-form solution) is transparent and traceable back to the math.

## Algorithms

- ⏳ **Linear Regression** — implemented two ways: via Gradient Descent (iterative optimization) and the Closed-form/Normal Equation solution, to compare both approaches.
- ⏳ **Logarithmic Regression** — fitting a logarithmic curve to non-linear data using derived update rules.
- ⏳ **Polynomial Regression / Curve Fitting** — solved using Gaussian Elimination to fit higher-degree polynomial curves to data.
- ⏳ **Exponential Regression** — coming soon.
- ⏳ **Logistic Regression** — coming soon, for classification-style problems.
- ⏳ **Multivariate Regression** — coming soon, extending linear regression to multiple input features.

More algorithms will keep getting added to this repository over time as I continue learning. Each addition will include the working code along with the mathematical reasoning behind it, so the repo doubles as both an implementation reference and a learning log.

## Why this project?

Understanding an algorithm by implementing it from the ground up builds a much deeper intuition than just using a pre-built library function. This project is my way of making sure I actually understand the derivations — the gradients, the loss functions, the linear algebra — rather than just knowing which function to call.

## Tools used

All development and experimentation for this project is done in Google Colab, with notebooks pushed directly to this repository.

---
Feel free to explore the code, and check back for updates as new algorithms get added!
