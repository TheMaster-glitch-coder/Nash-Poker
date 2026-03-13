# Nash Poker – River Stage Game Theory

This project analyzes a simplified **heads-up poker river scenario** using game theory. The goal is to model strategic interactions between players and compute optimal strategies using **Nash equilibrium**.

## Overview
On the river, players make decisions with complete community information but uncertain opponent hands. This project simplifies the environment by grouping hands into **hand-strength buckets** and computing equilibrium strategies.

## Method
- Generate hand strength using the **Treys poker hand evaluator**
- Group hands into buckets to reduce the strategy space
- Construct payoff matrices for possible betting strategies
- Compute **mixed-strategy Nash equilibria** using the **Nashpy** library

## Insights
The model provides insights into:
- Optimal **bluffing frequencies**
- **Value betting thresholds**
- Strategic behavior 

## Tech Stack
- Python
- NumPy
- Pandas
- Treys
- Nashpy

## Project Status
Completed
