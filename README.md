# "What Makes Democracies Greener? The Role of Pollution Offshoring" 

## Repository Structure

This is the data repository for the paper "What Makes Democracies Greener? The Role of Pollution Offshoring" by Tobias Böhmelt, Ella Henninger, and Thomas Bernauer.

- The main analyses can be found in **replication_code.rmd** and **replication_code - r_and_r.rmd**.
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
- Load data
- Create lagged and logged variables

3. Descriptives
- Table summary statistics

4. Analyses
- Models democracy and pollution outsourcing: Model group 1
- Models pollution outsourcing and environmental performance: Model group 2
- Plots model group 1
- Plots model group 2

5. Quantities of interest
- Simulated interaction effects
- Marginal effects plots
- Expected values: Model group 1 
- Expected values & first differences: Model group 2 

6. Robustness checks
- Replacing DV with PM2.5
- Replacing DV with carbon footprint
- Different outsourcing variables
- Alternative operationalization outsourcing
- Alternative operationalization democracy
- Additional controls
- Drop high-income states
- Alternative model specification