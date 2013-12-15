brainwallet-enhanced
====================

how to deal with bitcoin payments offline as good as online with an app for everyone


out of questions to the blockchain.info/wallet app, the wish for a better and more usable software arose...


BIP 21 is nice to hand over a request for payment to the customer. This works online only.
I have done that for online shops so far. Works fine for both parties so far.

BUT: for a offline store, e.g. at a RL market.. this is no good and the current available ios app does only help half the way (request payment, could send if sender is online)

imagine
* a place with low to no connection
* both parties are offline
* there we need something like an offline working web app and/or smartphone app - probably best utilizing BIP 70-72 if applicable in detail

(preparation)
seller:
* have a list of items and prices
buyer:
* have some bitcoin in the (brain)wallet

(on the market)
seller:
* show up address and amount to customer

customer:
* input / scan (qr) address and amount 
* type in (brainwallet passphrase) / select (& unlock) private key
* sign transaction
* (automatically) save transaction for later proof of payment
* hand over signed transaction to seller (as qr)
seller:
* input / scan (qr) transaction
* (automatically) check /compare transaction-details to fit the request
* hand over items

(later, e.g. after market day is over)
seller:
* send / release tx to network when online

also possible (other) use cases:
* prepare itemlist with prices (pro feature - possibly with extra one time fee for phone-apps)
* sweep funds by input / qr-scan
* to hand over a business card as qr could help in that app to connect the (new) contact with the transaction
* write & sign messages to a contact
* read & verify a message receives of a contact
* switch to online mode to behave like the BIP 21 version
* list & search & sort transactions (details e.g.: dtg, amount, sender, receiver, released(y/n) )
* create a number of (vanity) addresses
* edit address book
* ex- & import address book

1. did I miss some gap in the process?
2. any comments for improvement?
3. what is needed to build this? (would prefer a solution  )
4. who can help to make this happen like a brainwallet app?
