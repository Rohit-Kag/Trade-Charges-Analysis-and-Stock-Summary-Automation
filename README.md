# Kite-PnL
## The Kite PnL Problem Statement

This project addresses the challenge of processing intraday trading data provided in a CSV format. The task involves creating a summary Excel file that includes detailed analyses and calculations based on the trading data. 

### Problem Description
The client has provided an "orders" file containing information about trades made by an intraday trader in various stocks. The file includes fields such as timestamp, trade type (Buy or Sell), stock name, product type (MIS or CNC), quantity, average price, and status (Cancelled, Rejected, or Completed). The goal is to create a summary Excel file with three tables:

1. *Different types of charges for Individual trade*
2. *Instrument and Type wise analysis with weighted Avg. price & all calculated charges*
3. *Overall Summary of Stocks with Gross PnL, Net PnL, Total Charges, and % Charges on Gross PnL*

### Client Requirement
The client expects a Python program that processes the provided data and generates the summary Excel file. Additionally, the program should calculate transaction charges based on the information provided on the Zerodha website, specifically focusing on the Equity Intraday section and using NSE values for calculations.

### How to Use
1. *Clone the Repository:* Clone this repository to your local machine.
2. *Install Dependencies:* Install the required dependencies specified in the requirements.txt file.
3. *Run the Program:* Execute the Python program (main.py) to process the trading data and generate the summary Excel file.
4. *Review the Output:* Check the generated Excel file for the detailed summary and analyses of the trading data.

Resources
- [Zerodha - Equity Intraday Charges](https://zerodha.com/charges#tab-equities)

Contributors
- [Your Name](link to your GitHub profile)
