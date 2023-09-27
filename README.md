# Queue-Management-Optimization

## Objective:
This project aims to explore, simulate, and analyze various queue management policies and operator configurations within customer service call centers to understand the implications and efficiency of different structures and policies on average waiting times and overall service delivery.

## Initial Problem Framework:
The project simulates a system where the time between incoming phone calls follows an Exponential distribution with a mean of 14 minutes, and call durations are modeled by a Triangular distribution with parameters min=5, max=20, and most likely=10 minutes.

**Primary Scenarios:**
**Scenario A:**
System Structure: Single queue managed by two operators.
**Objective:** Investigate and analyze the average waiting time in a single-queue system, reporting the histogram and mean to determine the effectiveness of this configuration.
**Scenario B:**
**System Structure: ** Two queues with one operator each; incoming calls are allocated based on a “random” policy.
**Objective:** Explore and assess the operational impact and dynamics of a dual-queue system through the evaluation of the histogram and mean of the average waiting time.
**Advanced Problem Revision:**
The project scope extends by altering the average time between incoming phone calls to an Exponential mean of 5 minutes and introducing three operators, each with distinct service time distributions and individual queues.

**Operators 1 and 2:** Uniformly distributed service times between 5 to 20 minutes.
**Operator 3:** Normally distributed service time with a mean of 15 minutes and a standard deviation of 3 minutes.
**Extended Scenarios Objectives:**
**Objective a:** Develop utilization plots for each operator and analyze operational efficiency and capacity.
**Objective b:** Study individual waiting times for each operator to gauge customer wait experiences and service delivery under varied operator characteristics.
**Objective c:** Calculate a 95% confidence interval for the average waiting time for each operator, assessing reliability and consistency.
## Methodology:
Each scenario, both primary and advanced, is simulated for a duration of 6 hours with 50 replications to validate insights and to depict comprehensively and reliably the real-world implications.

## Usage:
This repository contains all the codes and results of the simulations and analyses carried out as part of this project. Feel free to explore, use, and adapt the material available for your needs, and do not hesitate to contribute or ask questions if you find areas that could be improved or clarified.

## Contribution:
If you find any bugs or areas of improvement, please create an issue or a pull request, and contributions are always welcome.
