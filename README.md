# Monty-Hall-Simulation

## Overview

This Jupyter Notebook provides simulations of the famous Monty Hall problem to demonstrate the validity of the counterintuitive solution. The problem, inspired by the game show Let's Make a Deal, involves determining if a contestant, when presented with three doors, one of which has a car behind, the others: goats, should switch their initially chosen door when the host reveals a goat behind one of the other doors. 


Through simulations with varying numbers of doors, the notebook shows:

- For the classic 3-door case, switching doors results in about a 67% win rate, while not switching leads to a 33% win rate

- As the number of doors increases to 100, the win rate for switching approaches 99%, demonstrating the advantage of switching

## Contents

The notebook contains the following sections:

- Explanation of the Monty Hall problem 

- Creating functions to simulate game iterations and calculate win rates

- Simulating the game with three doors, plotting win rates for switching vs. not switching

- Extending the simulation to one-hundred doors, again plotting the win rates 

- Discussion of the results and the intuition behind why switching is favourable

## Requirements

The notebook requires the following Python packages:

- Matplotlib

## Usage

The notebook can be run start-to-finish to view the simulations and resulting plots. Additional simulations can be run by modifying parameters like the number of doors or iterations.