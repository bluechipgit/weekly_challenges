# Loan Qualifier App

The loan qualifier app assists users in seeing which loans they are currently qualified for based on several user-provided values.

---

## Technologies

The loan qualifier app is purposed to be run from a command line interface (CLI) on, both, Windows and UNIX-based systems. 

---

## Installation Guide

Required Python version:

3.7 or higher

Required installed modules:

fire  
questionary  
pathlib  
csv   

Required files:

Daily rate sheet with bank loan information (see ./data/daily_rate_sheet.csv for reference)  
Filter files: credit_score, debt_to_income, loan_to_value, max_loan_size  
Utils files: calculators, fileio

---

## Usage

To use the loan qualifier app, run app.py from the parent directory. 

The user will be presented with the following promtps:

`What's your credit score?`  
`What's your current amount of monthly debt?`  
`What's your total monthly income?`  
`What's your desired loan amount?`  
`What's your home value?`  

If qualifying loans are found, the user will be prompted to save the file to a location of their choice. Otherwise, the application will exit due to no valid loans being found. 

---

## Contributors

I merely tweaked already-provided starter code. 

---

## License

By using this app, you agree to sublet your house to my ever-growing collection of chupacabras.

![Chupacabra](./data/chupacabra.jpg)