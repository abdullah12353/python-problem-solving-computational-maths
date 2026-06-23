# Python Problem Solving & Computational Mathematics

This repository contains selected Python coursework from my third-year **Problem Solving with Python** module during my BSc Mathematics at the University of Warwick.

The work applies Python to mathematical puzzles, stochastic simulation, recurrence relations, numerical experimentation and visualisation. The notebooks are intentionally kept close to their original exploratory form, but the repository has been organised to make the computational ideas clear to recruiters and technical reviewers.

## Project Overview

Across five assignments and one larger mini-project, I used Python to investigate mathematical problems by combining simulation, recurrence relations and visual analysis.

The notebooks demonstrate:

* Monte Carlo simulation
* Random processes and probability estimation
* Recurrence relations and difference equations
* Matrix-based numerical experiments
* Visualisation with Matplotlib
* Exploratory computational problem solving
* Translating mathematical reasoning into working Python code

## Assignment Summaries

### Assignment 1: Recurrence Periods Modulo 10

This notebook investigates a Fibonacci-style recurrence where each new term is calculated from the previous two terms modulo 10.

For every possible starting pair `(a, b)` with digits from 0 to 9, the code computes how long it takes before the recurrence returns to a previously seen pair. This gives a computational view of periodic behaviour in modular recurrence sequences.

### Assignment 2: Random Matrix Game

This notebook estimates the probability of winning a matrix-based game using random binary matrices.

For each matrix dimension, the code creates a shuffled matrix of zeros and ones, computes the determinant, and records whether the determinant is zero. The experiment compares the estimated probability of winning depending on whether the player starts first or second.

### Assignment 3: Random Hat Game

This notebook simulates a random number game where two numbers are repeatedly drawn from a list and replaced by their absolute difference until only one value remains.

The code runs repeated simulations for different starting values of `n`, plots histograms of final outcomes, and checks whether odd final results occur in a large case.

### Assignment 4: Random Walk Hitting Probability

This notebook studies a random walk where each step has size 1 or 2. The goal is to estimate the probability that the walk lands exactly on a target square.

The notebook combines simulation with a derived recurrence relation for the hitting probability. The resulting plot shows the probability converging towards `2/3`.

### Assignment 5: Spiral Walk Distance

This notebook simulates movement along a square spiral and measures the distance from the origin after each number of steps.

The notebook computes spiral coordinates, calculates Euclidean distance from the origin, and fits a polynomial curve to the observed distance values.

### Mini-Project: Water Bottle Game Simulation

The larger mini-project investigates a stochastic water bottle game involving two players:

* Player A distributes water across bottles.
* Player B randomly empties adjacent bottles.
* The game is tracked until a bottle exceeds the overfilling threshold.

The notebook uses Monte Carlo simulation to estimate how often the game is won by a given turn for different numbers of bottles. It also derives and plots difference equations for equal-splitting strategies under different game settings.

## Technologies Used

* Python
* NumPy
* Matplotlib
* Jupyter Notebook

## What I Learned

This module strengthened my ability to turn mathematical problems into computational experiments. In particular, it helped me build confidence using Python to test conjectures, simulate random processes, visualise results and connect numerical output back to mathematical reasoning.
