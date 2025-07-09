# Travelling Salesman Problem

## Description

This project focuses on solving the **Travelling Salesman Problem (TSP)** — a well-known NP-hard combinatorial optimization problem — using five different nature-inspired and evolutionary algorithms. TSP has wide-ranging applications in fields like logistics, route planning, manufacturing, and circuit design, where finding the most efficient path is critical.

The project is driven by a comparative implementation and analysis of the following algorithms:

- Firefly Algorithm  
- Genetic Algorithm with Crossover Search  
- Genetic Algorithm with Reinforcement Learning  
- Ant Colonisation Algorithm  
- Cuckoo Algorithm  

By exploring and testing each approach, the project aims to identify the strengths and trade-offs of different heuristic methods for solving TSP effectively.

---

## Highlights

- Implements five optimization algorithms for solving TSP.
- Comparative study based on:
  - Resolution quality
  - Convergence speed
  - Computational efficiency
- Firefly Algorithm utilizes light intensity to guide path optimization.
- Genetic Algorithms leverage crossover, mutation, and reinforcement learning for improved path refinement.
- Ant Colonisation Algorithm simulates foraging behavior to discover optimal routes.
- Cuckoo Algorithm introduces diversity via brood parasitism-inspired exploration.
- The Genetic Algorithm with Reinforcement Learning and Ant Colonisation Algorithm performed best overall.

---

## Methodology

### 1. Firefly Algorithm

Based on the natural behavior of fireflies, this algorithm uses the concept of light intensity to guide search agents toward brighter (better) solutions. Fireflies are attracted to each other based on their brightness, helping converge toward the optimal tour.

### 2. Genetic Algorithm with Crossover Search

This version of the Genetic Algorithm uses crossover and mutation operators to evolve a population of tours. It relies on selection, recombination, and mutation to iteratively improve the population and approach the optimal path.

### 3. Genetic Algorithm with Reinforcement Learning

An enhancement over the basic genetic algorithm, this version integrates reinforcement learning to adaptively improve performance based on feedback from previous generations. This helps the model avoid redundant exploration and focus on promising regions of the solution space.

### 4. Ant Colonisation Algorithm

Inspired by the foraging behavior of ants, this algorithm constructs tours using pheromone trails. Each ant probabilistically chooses the next city based on the intensity of pheromone and distance, gradually building optimal solutions over iterations.

### 5. Cuckoo Algorithm

Based on the brood parasitism of cuckoo birds, this algorithm explores the solution space by placing "eggs" (solutions) in random "nests" (locations). The method promotes diversity and avoids local optima through exploration and randomization.

---

## Comparative Analysis

Each algorithm was tested and evaluated based on resolution quality, convergence speed, and computational efficiency.

The results demonstrated that:

- **Genetic Algorithm with Reinforcement Learning** showed high solution quality and adaptive performance.
- **Ant Colonisation Algorithm** exhibited fast convergence with balanced computational cost.

Other algorithms also provided good results but had specific limitations in convergence rate or consistency across runs.

This project provides valuable insights into the practical application of nature-inspired and learning-based heuristics for NP-hard problems like TSP, contributing to the research on optimization techniques.
