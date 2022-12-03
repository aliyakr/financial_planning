# Module5Challenge
The task is to create:
1. A financial planner for emergencies.The members will be able to use this tool to visualize their current savings. The members can then determine if  they have enough reserves for an emergency fund.
2. A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.
# Technologies
- python 3.9.12
- JupyterLab
- libraries: pandas, matplotlib, os, requests, json, dotenv, alpaca-trade-api, MCForecastTools
- MacOs
### Financial planner for emergencies 
In <b>Step 1</b>:
1. Enter the current number of coins for each cryptocurrency asset held in the portfolio.
2. Enter the monthly amount for the member's household income. <br />
<br />There are 3 possible outcomes:
- total portfolio value succeeds the emergency fund value
- total portfolio value equals to the emergency fund value
- total portfolio value fails the emergency fund value
<img width="821" alt="Screen Shot 2022-10-17 at 8 39 06 PM" src="https://user-images.githubusercontent.com/111472420/196330262-77131450-6b6e-43ce-8988-4d92b5d125c2.png"> <br />

### Financial planner for retirement
There are two ready for use MCSimulator templates (for 30 and 10 years). <br />
You can adjust:
- current amount of shares held in both the stock (SPY) and bond (AGG) portion of the portfolio.
- start and end dates for collective data
- number of trading days (252 * years)
- stocks/bonds ratio (weights)
- number of simulations <br />

<i>The visualized results of your calculations will be saved in the same directory.</i><br />

<img width="1145" alt="Screen Shot 2022-10-17 at 8 54 05 PM" src="https://user-images.githubusercontent.com/111472420/196331751-e7844c2a-75c3-4777-b30e-f92cada81482.png"> <br />

![MC_10year_sim_plot](https://user-images.githubusercontent.com/111472420/196332183-25b85e23-990a-495c-8ae5-0297c3ca9ce5.png)
![MC_10year_dist_plot](https://user-images.githubusercontent.com/111472420/196332206-87bc050a-0fb9-4943-a758-d154b3d48f8f.png)
