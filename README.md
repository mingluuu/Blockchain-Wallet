# FinTechBootcamp_Assignments_19

**Overview**
----
Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. It integrates with the Ethereum blockchain network into in order to enable the customers to instantly pay the fintech professionals whom they hire with cryptocurrency. While Python was used for the back-end code, Streamlit enhances the front-end user experience.

**Requirements**
----
This project leverages python 3.7 and Streamlit, hashlib, web3, eth-tester, mnemonic and bip44.

The following libraries were used:

- Streamlit - Streamlit turns data scripts into shareable web apps in minutes.
- hashlib- This module implements a common interface to many different secure hash and message digest algorithms. In our application, we use SHA256 to return a hexdigest.
- web3.py - This is a Python library for connecting to and performing operations on Ethereum-based blockchains.
- eth-tester - This is a Python library that provides access to the tools we’ll use to test Ethereum-based applications.
- mnemonic - This is a Python implementation for generating a 12- or 24-word mnemonic seed phrase based on the BIP-39 standard.
- bip44 - This is a Python implementation for deriving hierarchical deterministic wallets from a seed phrase based on the BIP-44 standard.

Install the following librarie(s) in your terminal.
```
pip install streamlit        
pip install web3==5.17
pip install eth-tester==0.5.0b3 or pip install eth-tester
pip install mnemonic
pip install bip44
```

**Instructions**
----
## To start:
1. Download and install Ganache
2. Open Ganache and copy MNEMONIC key to `.env`
3. Simply run the following command in terminal under project directory.
```
streamlit run fintech_finder.py
```
4. Go to Ganache transaction page to check the transaction records

Below please see a sample of the Ganache Transactions page.

<img src="Figures/ganache _transaction.png" width="1000"/>
