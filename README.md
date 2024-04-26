# Dynaco Manufacturing Machine Breakdown Simulation

## Project Overview
This project involves creating a simulation model for Dynaco Manufacturing Company to predict machine breakdowns and associated repair times over 1000 weeks. This model helps in understanding the maintenance needs and scheduling, as well as estimating the operational downtime and its impact on the production process.

## Problem Statement
Dynaco's production process is heavily dependent on the continuous operation of its five machines. Unplanned breakdowns can lead to significant disruptions. By simulating these breakdowns and the subsequent repairs, Dynaco aims to gain insights into the average number of breakdowns per week and the repair time required.

## Data Summary
The simulation uses the following probability distributions for machine breakdowns and repair times:
- Machine Breakdowns per Week: A discrete probability distribution with probabilities ranging from 0.05 to 0.30 for 0 to 5 breakdowns.
- Repair Time: A discrete probability distribution with probabilities for 1, 2, or 3 hours required to fix a machine, with respective probabilities of 0.30, 0.50, and 0.20.

## Simulation Details
- Time Frame: 1000 weeks
- Objectives:
  - Calculate the average number of breakdowns per week.
  - Determine a 95% credible interval for the number of breakdowns per week.
  - Calculate the average weekly repair time.
  - Determine a 95% credible interval for the repair time per week.

## Methodology
A Monte Carlo simulation is conducted to sample from the given probability distributions. The simulation includes:
- Sampling the number of machine breakdowns per week.
- Sampling the repair time for each breakdown.
- Aggregating the data to calculate the required statistics.

## Results and Interpretation
The results of the simulation include:
- The average number of breakdowns per week.
- A 95% credible interval for the weekly breakdowns.
- The average weekly repair time.
- A 95% credible interval for the weekly repair time.

These results will guide maintenance scheduling and help in formulating strategies to minimize downtime.

## Tools and Technologies Used
- Python: For creating the simulation model and performing statistical calculations.
- Libraries: NumPy for numerical operations, Pandas for data manipulation, Seaborn, and Matplotlib for visualization.
- Jupyter Notebook: For documenting the simulation process and results.

## How to Run the Simulation
Instructions for setting up the environment, installing dependencies, and running the simulation model can be included in this section.

## Repository Structure
- machine_breakdown.ipynb: The Jupyter Notebook containing the simulation code and results.
- data/: A directory containing the probability distributions for machine breakdowns and repair times.

## Conclusion
This simulation provides Dynaco Manufacturing Company with a statistical foundation to anticipate machine breakdowns and optimize repair times, contributing to smoother operations and better maintenance planning.
