# Loan Payoff Simulator
A simple Python script for simulating payoff strategies for loans. It is a great tool if you are a student out of college and you are trying to figure out how to get your loans out of the way ASAP.

This script takes in a JSON file containing basic loan data (minimum payment, principal, and interest rate). You can select a payoff strategy from the following:
- Avalanche: Prioritize paying off higher interest rates while making all minimum payments. Once a loan is paid off, apply the payments for that loan to the highest priority loan that is not paid off.
- Snowball: Prioritize paying off lower balance loans while making all minimum payments. Once a loan is paid off, apply the payments for that loan to the highest priority loan that is not paid off.
- Minimum payment: Only make minimum payments on all loans.

The script outputs a JSON dump with information about the loans such as which order to pay them off in, how long it will take to pay all the loans off, and interest paid on the loans.

For more info, run `simulate.py --help`.

If you have any problems, please feel free to create Issue.
