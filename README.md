# Solar development stress tests with Monte Carlo Simulations

#### Create random variables of build costs and sale prices of developed residential solar projects to appreciate how detorirating economic conditions may impact Gross Revenue, Net Revenue, and Margins. This was created to compare a simulation to a base case and appreciate the volatility that arises in business.

## Features

- Triangular distributions for uncertain variables: system size, build cost, sale price.
- Monte Carlo simulation for gross revenues
- Cumulative net revenue calculation
- Plots for gross revenue, fixed and variable costs, net revenue, and cumulative net revenue


## Assumptions

- Simplified milestone payment amounts and cash flows from sales dates to three milestones
- Assumed industry standard converation rates and employee sales productivity
- Triangular distributions best describe randomd variable because they include minimum, mode, and max values. We are able to estimate maximum costs to build projects and the minimum prices we will sell developed projects for and have confidence concerning the mode.

## Requirements
- Python 3.x
- Pandas, Numpy, Matplotlib, OpenPyXL libraries

## Usage
1. Clone the repository
2. Install required libraries
3. Run the Python script (main.py)
4. View output data and plots

