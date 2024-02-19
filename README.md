# Cryptocurrency Wallet

## Overview

This project implements a cryptocurrency wallet application that allows users to manage Ethereum transactions. Users can:

- Generate a new Ethereum account instance using their mnemonic seed phrase.
- Fetch and display the account balance associated with their Ethereum account address.
- Calculate the total value of an Ethereum transaction (including gas estimate) to pay a candidate for their work.
- Digitally sign a transaction to pay a candidate.
- Review the transaction hash code associated with the validated blockchain transaction.

## Features

- **Generate Account:** Create a new Ethereum account instance.
- **Fetch Balance:** Display account balance.
- **Calculate Transaction Value:** Determine total value of a transaction.
- **Send Transaction:** Digitally sign and send a transaction.
- **Review Transaction:** View transaction hash code.

## Technologies Used

- Python
- Streamlit
- Web3.py

## Usage

To use this application, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies (`streamlit`, `web3`, etc.) using `pip`.
3. Run the Streamlit application using the command `streamlit run krypto_jobs.py`.
4. Use the application interface to perform the desired actions.

## Screenshots

Include screenshots of the application interface and any relevant transactions or balances from your Ethereum account.

![Ganache Account](Starter_Code\Images\ganche_account_after_transaction.png "Ganache Account")

![Payment Transaction](Starter_Code\Images\ganche_transaction.png "Payment Transaction")