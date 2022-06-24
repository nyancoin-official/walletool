# walletool
A python3 tool for reading NYAN wallet.dat files 

Installation
------------

* Install Python 3.x.
* Install bdb-4.8.
* Install the `bsddb3` module.

Extracting private keys from Nyancoin-QT wallets
-----------------------------------------------------------

* Have your `wallet.dat` handy.
* For Nyancoin, run `python wt_extract_keys.py -d wallet.dat -v nyan`
* For Nyancoin testnet, run `python wt_extract_keys.py -d wallet.dat -v nyan-testnet`
* For Nyancoin regtest, run `python wt_extract_keys.py -d wallet.dat -v nyan-regtest`

A list of Nyancoin addresses / compressed private keys is printed.
