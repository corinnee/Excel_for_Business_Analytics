
# Excel Solver for Market Demand Allocation

## Overview

This repository contains an Excel Solver model and a managerial report completed as part of the 'Management Analytics' module at the University of Kent. The project involves optimising the allocation of production units across TelecomOne's manufacturing plants to minimize costs while meeting market demands.

## Project Description

TelecomOne operates manufacturing plants in Baltimore, Memphis, Wichita, Wyoming, and Salt Lake City, serving markets in Atlanta, Boston, Chicago, Denver, Omaha, and Portland. The pre-provided data included production, inventory, and transportation costs, plant capacities, fixed monthly costs, and monthly demand.

## Optimisation Model

The optimisation model uses the following components:

- Decision Variables:
  - Xi: Binary variable representing whether plant i is in operation.
  - Yij: Allocation of demand from market j to plant i.

- Objective Function:
  - Minimize total cost = ∑i (Fi Xi) + ∑i∑j (Vij Yij), where Fi and Vij are cost parameters.

- Constraints:
  - Capacity constraints for each plant.
  - Demand constraints for each market.
  - Binary constraints for plant operation.

## Usage

1. **Excel Solver**: To find the optimal solution, use the Excel Solver. Go to the Data tab and select "Solve." Preset data and constraints are already selected.

2. **Adjust Data**: You can alter costs, capacities, and demands in the "Table of Data Given" to explore different scenarios.

## Files

- `Managment_Analytics_Report.pdf`: Managerial report summarizing findings and recommendations.
- `excel_solver_for_cost_allocation.xlsx`: Excel file containing the optimisation model.
