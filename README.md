# HW-5-APIs
**Unit 5 - Financial Planning**

## Table of Contents
- [The Scenario](#the-scenario)
- [Navigating the GitHub](#navigating-the-github)
- [Important Notice](#important-notice)
- [Part 1 - Personal Finance Planner](#part-1---personal-finance-planner)
    * [Savings Health Analysis](#savings-health-analysis)
- [Part 2 - Retirement Planning](#part-2---retirement-planning)
    * [Monte Carlo Simulation](#monte-carlo-simulation)
    * [Retirement Analysis](#retirement-analysis)
- [Part 3 OPTIONAL - Early Retirement](#part-3-optional---early-retirement)
    * [Five Years Retirement Option](#five-years-retirement-option)
    * [Ten Years Retirement Option](#ten-years-retirement-option)

## The Scenario

You decided to start a FinTech consultancy firm, and you want to make a difference by working on projects with high social impact in local communities. You just won your first contract to help one of the biggest credit unions in your area. They want to create a tool that helps their members enhance their financial health. The Chief Technology Officer (CTO) of the credit union asked you to develop a prototype application to demo in the next credit union assembly.

The credit union board wants to allow the union's members to assess their monthly personal finances, and also be able to forecast a reasonably good retirement plan based on cryptocurrencies, stocks, and bonds.
In this homework activity, you will use all the skills you have learned until now - focusing on using APIs as part of the technical solution - to create two financial analysis tools.

The first will be a personal finance planner that will allow users to visualize their savings composed by investments in shares and cryptocurrencies to assess if they have enough money as an emergency fund.
The second tool will be a retirement planning tool that will use the Alpaca API to fetch historical closing prices for a retirement portfolio composed of stocks and bonds, then run Monte Carlo simulations to project the portfolio performance at 30 years. You will then use the Monte Carlo data to calculate the expected portfolio returns given a specific initial investment amount.

## Navigating the GitHub

In the Images folder, you will find a collection of the plots made using the code.

The following was provided at the beginging of the assessment and can be found in the Starter_code folder:

- [MCForecastTools.py](https://github.com/RPSangil/HW-5-APIs/blob/41d60a9009280ed442a5191559990de340cae685/Starter_Code/MCForecastTools.py)
- [Financial Planner Starter Notebook](https://github.com/RPSangil/HW-5-APIs/blob/41d60a9009280ed442a5191559990de340cae685/Starter_Code/financial-planner.ipynb)

In the Worked_Code folder you will find:

- [MCForecastTools.py](https://github.com/RPSangil/HW-5-APIs/blob/41d60a9009280ed442a5191559990de340cae685/Worked_Code/MCForecastTools.py)
- [Financial Planner Notebook](https://github.com/RPSangil/HW-5-APIs/blob/9742b1fbc815defc94a9dda43611bc4ffe562221/Worked_Code/financial-planner.ipynb) - The code I have written for this notebook.


## Important Notice

1. Please view this github in `Day Theme - Light Default` so that headers and axises on the plots show.

## Part 1 - Personal Finance Planner

- The current value of your 1.2 BTC $36526.17.
- The current value of your 5.3 ETH $11863.32.

- The current AGG closing price is $103.02.
- The current SPY closing price is $445.04.

- The current value of your 200 AGG Shares is $89008.00.
- The current value of your 50 SPY Shares is $5151.00.

### Savings Health Analysis

<ins> Savings Composition </ins>

![Savings Composition](https://github.com/RPSangil/HW-5-APIs/blob/8c1930d221f7c07f1459346441635439c5cb7e7b/Images/Savings_Composition.png)

- Your current emergency fund is $36000.00.
- Your current total is $141976.12.
- Your current savings health is +$105976.12.

## Part 2 - Retirement Planning

### Monte Carlo Simulation

<ins> 1000 Simulations of Cumulative Portfolio Return Trajectories Over the Next 7560 Trading Days </ins>

![1000 Simulations of Cumulative Portfolio Return Trajectories Over the Next 7560 Trading Days](https://github.com/RPSangil/HW-5-APIs/blob/9742b1fbc815defc94a9dda43611bc4ffe562221/Images/1000_Simulations_of_Cumulative_Portfolio_Return_Trajectories_over_the_Next_7560_Trading_Days.png)

<ins> Distribution of Final Cumulative Returns Across all 1000 Simulations </ins>

![Distribution of Final Cumulative Returns Across all 1000 Simulations](https://github.com/RPSangil/HW-5-APIs/blob/9742b1fbc815defc94a9dda43611bc4ffe562221/Images/Distribution_of_Final_Cumulative_Returns_Across_all_1000_Simulations.png)

### Retirement Analysis

<ins>Summary Statistics from the Monte Carlo Simulation Results </ins>

![Retirment Analysis : Summary Statistics from the Monte Carlo Simulation Results](https://github.com/RPSangil/HW-5-APIs/blob/9742b1fbc815defc94a9dda43611bc4ffe562221/Images/Retirment%20Analysis%20-%20Summary%20Statistics%20from%20the%20Monte%20Carlo%20Simulation%20Results.PNG)

There is a 95% chance that an initial investment of $20000.00 in the portfolio over the next 30 years will end within in the range of $55456.17 and $496546.21.

There is a 95% chance that an initial investment of $30000.00 in the portfolio over the next 30 years will end within in the range of $83184.25 and $744819.32.

## Part 3 OPTIONAL - Early Retirement

### Five Years Retirement Option

<ins> 500 Simulations of Cumulative Portfolio Return Trajectories Over the Next 1260 Trading Days </ins>

![5 yr 500 Simulations of Cumulative Portfolio Return Trajectories Over the Next 1260 Trading Days](https://github.com/RPSangil/HW-5-APIs/blob/8c1930d221f7c07f1459346441635439c5cb7e7b/Images/5yr_500_Simulations_of_Cumulative_Portfolio_Return_Trajectories_over_the_Next_1260_Trading_Days.png)

<ins> Distribution of Final Cumulative Returns Across all 500 Simulations </ins>

![5 yr Distribution of Final Cumulative Returns Across all 500 Simulations](https://github.com/RPSangil/HW-5-APIs/blob/8c1930d221f7c07f1459346441635439c5cb7e7b/Images/5yr_Distribution_of_Final_Cumulative_Returns_Across_all_500_Simulations.png)

<ins>Summary Statistics from the Monte Carlo Simulation Results </ins>

![5yr : Summary Statistics from the Monte Carlo Simulation Results](https://github.com/RPSangil/HW-5-APIs/blob/8c1930d221f7c07f1459346441635439c5cb7e7b/Images/Five%20Year%20Retirement%20Option%20-%20Summary%20Statistics%20from%20the%20Monte%20Carlo%20Simulation%20Results.PNG)

There is a 95% chance that an initial investment of $20000.00 in the portfolio over the next 5 years will end within in the range of $18097.96 and $42468.09.

### Ten Years Retirement Option

<ins> 500 Simulations of Cumulative Portfolio Return Trajectories Over the Next 2520 Trading Days </ins>

![10 yr 500 Simulations of Cumulative Portfolio Return Trajectories Over the Next 2520 Trading Days](https://github.com/RPSangil/HW-5-APIs/blob/8c1930d221f7c07f1459346441635439c5cb7e7b/Images/10yr_500_Simulations_of_Cumulative_Portfolio_Return_Trajectories_over_the_Next_2520_Trading_Days.png)

<ins> Distribution of Final Cumulative Returns Across all 500 Simulations </ins>

![10 yr Distribution of Final Cumulative Returns Across all 500 Simulations](https://github.com/RPSangil/HW-5-APIs/blob/8c1930d221f7c07f1459346441635439c5cb7e7b/Images/10yr_Distribution_of_Final_Cumulative_Returns_Across_all_500_Simulations.png)

<ins>Summary Statistics from the Monte Carlo Simulation Results </ins>

![10yr : Summary Statistics from the Monte Carlo Simulation Results](https://github.com/RPSangil/HW-5-APIs/blob/8c1930d221f7c07f1459346441635439c5cb7e7b/Images/Ten%20Year%20Retirement%20Option%20-%20Summary%20Statistics%20from%20the%20Monte%20Carlo%20Simulation%20Results.PNG)

There is a 95% chance that an initial investment of $20000.00 in the portfolio over the next 10 years will end within in the range of $20142.63 and $69556.30.