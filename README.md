# The Kite PnL Problem Statement

## Description
The Kite PnL Problem Statement project involves processing intraday trading data provided in a CSV format. The goal is to create a summary Excel file that encompasses detailed analyses and calculations based on the trading data.

## Problem Statement
The client has provided an "orders" file containing information about trades made by an intraday trader in various stocks. The file includes fields such as timestamp, trade type (Buy or Sell), stock name, product type (MIS or CNC), quantity, average price, and status (Cancelled, Rejected, or Completed). The objective is to create a summary Excel file with three tables:
1. Different types of charges for Individual trade
2. Instrument and Type-wise analysis with weighted average price & all calculated charges
3. Overall Summary of Stocks with Gross PnL, Net PnL, Total Charges, and % Charges on Gross PnL

## Client Requirements
The client expects a Python program that processes the provided data and generates the summary Excel file. Additionally, the program should calculate transaction charges based on the information provided on the Zerodha website, specifically focusing on the Equity Intraday section and using NSE values for calculations.

## Implementation
The project is implemented using Python programming language. Key libraries utilized include:
- *pandas*: For data manipulation and analysis.
- *numpy*: For mathematical operations and array manipulation.
- *matplotlib*: For data visualization and plotting.

## How to Run the Program
1. Ensure Python is installed on your system.
2. Clone the repository to your local machine.
3. Make sure you have the required libraries installed:
   - pandas
   - numpy
   - matplotlib
4. Execute the main Jupyter Notebook main.ipynb to process the trading data and generate the summary Excel file.

## File Structure
- main.ipynb: Jupyter Notebook for processing the trading data and generating the summary Excel file.
- data/: Directory containing the input CSV file provided by the client.
- output/: Directory where the generated summary Excel file will be saved.

## Example Usage
Open main.ipynb in a Jupyter Notebook environment and execute the cells to run the program.

## Resources
- [Zerodha - Equity Intraday Charges](https://zerodha.com/charges#tab-equities)

## Contributors
- Rohit Kag.https://github.com/Rohitkag03/Kite-PnL
