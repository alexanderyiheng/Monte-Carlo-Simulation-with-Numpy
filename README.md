# Monte Carlo Simulation for Profit Analysis
This repository contains a Python script for conducting a Monte Carlo Simulation to estimate the profit distribution of launching a new product under pure/perfect competition market conditions. The simulation considers the total profit as a function of the quantity sold, selling price, variable cost, and fixed cost, incorporating uncertainty in several of these parameters.

## Overview
The script performs a Monte Carlo Simulation to analyze the potential profitability of producing and selling a new product. It takes into account the randomness associated with the quantity sold (Q), selling price (P), and variable cost (V), and calculates the total profit (TP) for a large number of simulated scenarios.

## Formula Used
The total profit (TP) is calculated using the formula:

TP = (Q * P) - (Q * V + F)
where:

Q is the Quantity Sold,
P is the Selling Price,
V is the Variable Cost,
F is the Fixed Cost.

Parameters
Quantity Sold (Q) follows a uniform distribution between 8,000 and 12,000.
Selling Price (P) and Variable Cost (V) are modeled as normal distributions with means and standard deviations of (10, 3) and (7, 2) respectively.
Fixed Cost (F) is set at $5,000.

## Simulation Results
The script outputs the expected value, standard deviation, percentiles, and probabilities of making a loss or significant profit from the simulation, providing valuable insights for decision-making.

## Usage
To run this simulation, ensure you have Python and NumPy installed. Execute the script using your preferred Python environment. The script will output statistical summaries and a histogram of the profit distribution.

## Acknowledgments
This project was inspired by and adapted from a series of educational videos on Monte Carlo Simulation by StatQuest with Josh Starmer. 
https://www.youtube.com/playlist?list=PLDU1w44nwfPMAtwTo2q08oQmd5fDAXaK8
The concepts and examples provided in these videos were instrumental in developing this simulation. Special thanks to Josh Starmer for the clear and insightful explanations that made this project possible.

## License
This project is open source and available under the MIT License.

