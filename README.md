# Commodity Derivatives Pricing Engine (C++ & Python)

A high performance C++ Monte Carlo simulation.

## Key Features
* **C++ Monte Carlo Engine:** Simulates 1,000,000 Geometric Brownian Motion (GBM) price paths in **~30 milliseconds** using `std::mt19937_64` (Mersenne Twister) and C++ `<chrono>` benchmarking.
* **Compiler Optimisation:** Utilizes GCC level-3 optimization flags (`-O3`) for vectorised CPU loop execution.
* **Analytical Derivatives Models:** Implements the **Cost of Carry Model** for coffee futures and the **Black-Scholes / Binary Option Model** for structured client hedging scenarios.


# Compile with level-3 optimizations
g++ -O3 src/monte_carlo.cpp -o monte_carlo

# Run binary executable
./monte_carlo
