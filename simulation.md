# Interval Coverage & Monte Carlo Simulations

## 📌 Project Overview
This project implements simulations and algorithms for interval coverage problems on [0,1], including:
- Checking connectivity of intervals.
- Calculating the union length.
- Monte Carlo simulations to estimate coverage probabilities.
- Estimating the expected number of points to cover [0,1].

## ✅ Features
- **Functions implemented**:
  - `is_connected` – Check if sorted points cover [0,1].
  - `union_length` – Compute union length of intervals.
  - `union_length_distribution` – Monte Carlo simulation for union length.
  - `plot_length_density` – Visualize length distribution.
  - `covering_prob` – Compute coverage probability for n points.
  - `plot_covering_prob` – Plot coverage probability vs number of points.
  - `mean_cover_time` & `mean_cover_time2` – Estimate mean points for full coverage.
- Includes **comprehensive test suite** with `pytest`.

## 🛠 Technologies
- Python 3
- NumPy
- Matplotlib
- Pytest

## ▶️ How to Run
```bash

# Install dependencies
pip install numpy matplotlib pytest

# Run simulations
python coverage_simulations.py

# Run tests
pytest test_coverage_simulations.py
