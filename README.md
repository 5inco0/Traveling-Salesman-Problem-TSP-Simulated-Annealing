This repository contains a Python implementation of the Traveling Salesman Problem (TSP) solved using the Simulated Annealing algorithm.
The project features a real-time animation that visualizes how the algorithm explores the search space and converges toward an optimal route.
It uses the Metropolis-Hastings criterion to escape local minima by occasionally accepting "worse" paths based on a cooling temperature.

Dynamic Visualization: A dual-plot animation using matplotlib.animation:

Route Evolution: Shows the path connecting all the cities as it optimizes.

Convergence Plot: Tracks the total distance reduction over the iterations.

Distance Matrix: Efficiently calculates Euclidean distances between all nodes using NumPy.


Algorithm: Markov Chain Monte Carlo (MCMC) / Simulated Annealing.

Libraries: numpy, matplotlib, random.

Linux Support: Includes a configuration fix for TkAgg backends to ensure smooth animation on Linux systems

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/InigoPeLo/Traveling-Salesman-Problem-TSP-Simulated-Annealing.git
2. **Install Dependencies**
3. ```bash
   pip install -r requirements.txt
2. **Choose the number of cities you want to simulate**
3. **Run the notebook**


