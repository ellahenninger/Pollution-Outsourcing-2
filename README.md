# "What Makes Democracies Greener? The Role of Pollution Offshoring" 

## Repository Structure

This is the data repository for the paper "What Makes Democracies Greener? The Role of Pollution Offshoring" by Tobias Böhmelt, Ella Henninger, and Thomas Bernauer.

- The main analyses can be found in **replication_code.rmd**.
- All relevant plots are stored in *plots*.
- The relevant data can be found under *data*.

## Data
 - **Outsourcing data**: Presberger and Bernauer (2023), https://www.sciencedirect.com/science/article/pii/S0959378023000031?via%3Dihub
 - **Pollution data**: Van Donkelaar et al. (2021), https://pubs.acs.org/doi/full/10.1021/acs.est.1c05309
 - **Main data**: Quality of Governance database (QoG), https://www.gu.se/en/quality-government/qog-data
 - **Economic data**: World Development Indicators (2023), https://databank.worldbank.org/source/world-development-indicators#
 - **Democracy data**: V-Dem (2023), https://www.v-dem.net/data/the-v-dem-dataset/
 

## Code Structure

The code in **replication_code.rmd** is structured as follows:

1. Set up

2. Preparatory steps
2.1 Load data
2.2 Create lagged and logged variables

3. Descriptives
3.1 Table summary statistics
3.2 Correlations
3.3 Trends

4. Analyses
4.1 Models democracy and pollution outsourcing: Model group 1
4.2 Models pollution outsourcing and environmental performance: Model group 2
4.3 Plots model group 1
4.4 Plots model group 2

5. Quantities of interest
5.1 Simulated interaction effects
5.2 Marginal effects plots
5.3 Expected values: Model group 1 (within)
5.4 Expected values: Model group 1 (Between)
5.5 Expected values & first differences: Model group 2 (within)
5.6 Expected values & first differences: Model group 2 (between)

6. Robustness checks
6.1 Replacing DV with PM2.5
6.2 Replacing DV with carbon footprint
6.3 Different outsourcing variables
6.4 Alternative operationalization outsourcing
6.5 Alternative operationalization democracy
6.6 Additional controls
6.7 Drop high-income states
6.8 Sample split instead of interaction term