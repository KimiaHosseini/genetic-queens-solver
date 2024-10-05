# genetic-queens-solver

## Overview

This repository contains a solution to the Eight Queens problem using a Genetic Algorithm (GA). The objective of the problem is to place eight queens on a standard 8x8 chessboard such that no two queens can attack each other, which means no two queens can be in the same row, column, or diagonal.
What is the Genetic Algorithm?

The Genetic Algorithm is a heuristic optimization technique inspired by natural selection. It involves the following steps:

Population Generation: A set of potential solutions (chromosomes) is randomly created.
Fitness Evaluation: Each chromosome is evaluated based on a fitness function.
Selection: The fittest chromosomes are selected to create the next generation.
Crossover and Mutation: Selected chromosomes are combined (crossover) and mutated to introduce diversity in the search space.

This approach is used to iteratively evolve the population towards a valid solution to the Eight Queens problem.

## Features

Chromosome Representation: Each chromosome represents a potential arrangement of queens on the chessboard.
Fitness Function: Determines how many queens are non-conflicting in a given arrangement.
Selection Process: Utilizes a method to select the fittest individuals for the next generation.
Crossover and Mutation: Introduces genetic diversity to avoid local minima and find the optimal solution.
Visualization: Displays the fitness scores of each generation and the final configuration of the queens.

## Project Structure

eight-queens-problem.ipynb: Jupyter Notebook containing the entire implementation of the Genetic Algorithm.
Population Initialization: Functions to initialize the population with random placements of queens.
Fitness Calculation: Functions to evaluate how many queens are safe from attacks.
Selection, Crossover, Mutation: Core functions that perform genetic operations to evolve the population.
Visualization: Graphical output showing the fitness progression over generations and the final solution.
