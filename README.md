# Stock Earnings Analysis Tool

This project is a Python-based tool for fetching and analyzing stock earnings data. It utilizes data from the FinancialModelingPrep API to retrieve earnings information for US stocks. The tool calculates year-over-year earnings growth and generates an Excel spreadsheet with the collected data.

Please note that only US stocks are available for searching in the free plan of the FinancialModelingPrep API.

## Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/govindKulk/python_stock_analysis.git
```

## Navigate the project directory

```bash
cd python_stock_analysis
```
## Install the required libraries

```bash
pip install -r requirements.txt
```
## Create .env file and paste your own FinancialModelling API key

```bash
FMP_API_KEY=your_api_key_here

```
## Usage

```bash
Run the script python main.py

```
## Additional Notes

1. Only us stocks are available to search in free plan
2. Only following stocks have valid earnings for ongoing week
    DIS.NE (Disney)
    AMD.NE (AMD)
    CBST.NE (Columbia Banking System)
3. Close the EarningsReport.xlsx before re-running the script. It imposes the permission issues on windows.

## Contribution and Feedback
Feel free to give feedback on this program. 
Regards: Govind Kulkarni
### kulkarnigovind2003@gmail.com ###
