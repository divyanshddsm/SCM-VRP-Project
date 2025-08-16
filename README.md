🚚 Vehicle Routing Optimization using Genetic Algorithm

This project implements a Genetic Algorithm (GA) to solve the Capacitated Vehicle Routing Problem (CVRP) — a core challenge in supply chain and logistics optimization.

The goal is to determine efficient delivery routes for a fleet of vehicles starting from a central warehouse to multiple retail stores, while minimizing the total travel distance and ensuring:

All customer demands are met.

Vehicle capacity constraints are respected.

Each retail store is visited exactly once.

🔑 Features

Genetic Algorithm implementation with chromosome encoding, selection, crossover, mutation, and elitism.

Fitness function based on the reciprocal of total distance.

Case studies (10 scenarios) with varying customers, vehicles, and capacities.

Visualization tools for:

Fitness vs. generation trends.

Optimal delivery routes on a 2D plane.

Scalable approach adaptable to different supply chain setups.

📊 Results

Successfully produced near-optimal solutions across all test cases.

Demonstrated clear trade-offs between fleet size, route efficiency, and delivery coverage.

Outperformed naive allocation strategies by significantly reducing total travel distance.

🚀 Future Enhancements

Support for heterogeneous vehicle capacities.

Multi-depot optimization for complex networks.

Time-window constraints for real-world delivery scheduling.

Extension to three-echelon routing problems.
