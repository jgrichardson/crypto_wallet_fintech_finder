# Crypto Wallet and FinTech Finder Application

This is a FinTech marketplace where people can list services and their hourly rates. People who want to hire them can pay them in Ether. This app uses a private blockchain for testing.


## Screenshots

App Home Page

![App Home Page](images/home.png)

Transaction Sent

![Transaction Sent](images/Sent_Transaction_Proof.png)

Transaction Proof

![Transaction Proof](images/Transaction_Sent_Proof.png)

Balance Proof

![Balance Proof](images/Balance_Proof.png)

## Dependencies

* Download and install Ganache

## Instructions

* Clone this repo to your local machine

'''
git clone https://github.com/jgrichardson/crypto_wallet_fintech_finder.git
'''

* Change directories to the cloned repo

'''
cd crypto_wallet_fintech_finder
'''

* Install the required dependencies

'''
pip install -r requirements.txt
'''

Paste your mnemonic phrase into your .env file:

'''
MNEMONIC = "<SEED_PHRASE>"
'''

Start Streamlit

'''
streamlit run fintech_finder.py
'''

## License

The source code for the application is licensed under the MIT license, which you can find in the LICENSE file in this repo.